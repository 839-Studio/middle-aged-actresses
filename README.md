## ["数说｜海清说中年女演员没戏演，这可能不是夸张"](https://www.thepaper.cn/newsDetail_forward_4050096)

1. ["the_four.csv"](https://github.com/839-Studio/middle-aged-actresses/blob/master/the-four.csv)包含马伊琍、海清、姚晨、宋佳的所有作品及相关信息。

actress - 演员姓名<br />
drama/movie - 参演电影/电视剧名<br />
year - 电影/电视剧上映/首播年份<br />
age - 上映/首播时该演员年龄<br />
douban_score - 电影/电视剧豆瓣评分<br />
role - 该演员在该作品中的身份（大部分是演员，偶尔有演员+制片人）<br />
leading - 该演员在该作品的演员表中是否位列前五<br />
award - 该演员因该作品获得的主要奖项（不一定完整）<br />
nomination - 该演员因该作品获得的主要提名（排除最终获奖的提名；不一定完整）<br />
source - 除去[豆瓣电影](https://movie.douban.com/)以外的来源<br />

![previous works of the four actresses](http://image.thepaper.cn/www/image/26/109/271.jpg)

2. ["china_drama_2018.csv"](https://github.com/839-Studio/middle-aged-actresses/blob/master/china_drama_2018.csv)包含所有2018年首播的中国电视剧及演员信息。

name - 电视剧名<br />
link - 电视剧的豆瓣链接<br />
actor_link - 该剧所有演员的豆瓣链接<br />
actor - 该剧的所有演员的名字

![actors and actresses in 2018's Chinese TV dramas by age](http://image.thepaper.cn/www/image/26/109/858.jpg)

3. ["china.csv"](https://github.com/839-Studio/middle-aged-actresses/blob/master/china.csv), ["japan.csv"](https://github.com/839-Studio/middle-aged-actresses/blob/master/japan.csv), ["korea.csv"](https://github.com/839-Studio/middle-aged-actresses/blob/master/korea.csv)和["us.csv"](https://github.com/839-Studio/middle-aged-actresses/blob/master/us.csv)分别包含了中日美韩四国1999年到2018年间最受关注的电影/电视剧的主演信息。<br />
筛选标准是豆瓣上该作品的标记数量。中国选取了这20年里每年最多标注了10部电影和10部电视剧，其他国家分别是5部电影和5部电视剧。

actor - 演员姓名<br />
name - 电影/电视剧名<br />
year - 电影上映/电视剧首播年份<br />
variable - 该演员在该电影/电视剧演员表中的顺序（"actor1"即为第一个）<br />
type - drama是指电视剧，movie是指电影<br />
BirthYear - 演员出生年份<br />
gender - 演员性别<br />
age - 该演员在电影上映/电视剧首播时的年龄

![ages of actors and actresses in popular TV dramas](http://image.thepaper.cn/www/image/26/107/944.jpg)

4. ["china_actor.csv"](https://github.com/839-Studio/middle-aged-actresses/blob/master/china_actor.csv)包含了964个中国演员的个人信息，在这个选题里主要用于匹配演员得出演员某作品上映时的年龄。

actor - 演员名字<br />
actor.link - 该演员的豆瓣链接<br />
info - 该演员豆瓣主页上的信息<br />
BirthYear - 该演员的出生年份<br />
gender - 该演员的性别
age - 该演员2018年时的年龄

5. 引用规范
本文数据采用 [CC BY 4.0.](https://creativecommons.org/licenses/by/4.0/) 进行授权。引用是需标准来源为“澎湃新闻-美数课栏目”。

如有问题，欢迎邮件联系liuchang(at)sixthtone.com.

| COLUMN_NAME      | DESCRIPTION                            | Sample Data                                              | DATA_TYPE    |
|------------------|---------------------------------------------|---------------------------------------------|--------------|
| url              | 當前網址url                            | url:"http://l70157.pixnet.net/blog/post/49484928"        | varchar(255) |
| country          | 瀏覽者所在的國家(如：tw、cn)           | country:"CA"                                             | varchar(2)   |
| city             | 瀏覽者所在區域                         | city:""                                                  | varchar(100) |
| resolution       | 瀏覽者螢幕大小                         | resolution:"768x1024"                                    | varchar(10)  |
| browser          | 瀏覽者瀏覽器                           | browser:"Mobile Safari"                                  | varchar(50)  |
| browser_version  | 瀏覽者瀏覽器版本且 Hash 過             | bro wser_version:"7.0"                                   | varchar(25)  |
| os               | 瀏覽者的os類型                         | os:"iOS"                                                 | varchar(50)  |
| os_version       | 瀏覽者的os版本且 Hash 過               |                                                          | varchar(25)  |
| device_marketing | 瀏覽者裝置市場名稱且 Hash 過           |                                                          | varchar(80)  |
| device_brand     | 瀏覽者裝置品牌名稱且 Hash 過           |                                                          | varchar(50)  |
| cookie_pta       | 瀏覽者cookie且 Hash過                  |                                                          | varchar(24)  |
| date             | 瀏覽日期 yyyymmdd                      | date:"20160101"                                          | integer      |
| timestamp        | 瀏覽時間timestamp                      | timestamp:"1451593800"                                   | integer      |
| hour             | 瀏覽時間(小時)                         | hour:"4"                                                 | smallint     |
| author_id        | 文章作者帳號                           | author_id:"l70157"                                       | varchar(64)  |
| category_id      | 文章分類id                             | category_id:"國內旅遊"                                   | varchar(64)  |

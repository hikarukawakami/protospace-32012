#テーブル設計

## users テーブル
|  Columm     |  Type    |  Options    |
|  --------   |  ------  |  ---------  |
|  password   |  string  |  NOT FULL   |
|  name       |  string  |  NOT FULL   |
|  profile    |  string  |  NOT FULL   |
|  occupation |  string  |  NOT FULL   |
|  pasition   |  string  |  NOT FULL   |
## prototypesテーブル
|  Columm     |  Type        |  Options    |
|  --------   |  ----------  |  ---------  |
|  title      |  string      |  NOT FULL   |
|  catch_copy |  text        |  NOT FULL   |
|  concept    |  text        |  NOT FULL   |
|  image      |  ----------  |  ---------  |
|  user       |  references  |  ---------  |
## commentsテーブル
|  Columm     |  Type        |  Options    |
|  --------   |  ----------  |  ---------  |
|  text       |  text        |  NOT FULL   |
|  user       |  references  |  ---------  |
|  prototype  |  references  |  ---------  |
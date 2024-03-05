# Event Title
## INPUT
String title
## OUTPUT
Title Obj
|level|title|type|description|
|---|---|---|---|
|1|budget|String|budget|
|1|category1|String|category 1|
|1|category2|String|category 2|
|1|isSpend|boolean|+,-|
|1|price|Integer||
## BOUNDary
### 1) Parse Title By Space
```
"MS SVTM TRANSPORT - 30"
```
### 2) Assemble into Title Obj
|level|title|type|description|
|---|---|---|---|
|1|category1|String|title[0]|
|1|category2|String|title[1]|
|1|budget|String|title[2]|
|1|isSpend|boolean|title[3] +:false ; -:true|
|1|price|Integer|title[4]|

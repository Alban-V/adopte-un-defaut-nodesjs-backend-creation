# Dictionnaire de données "Adopte un défaut"

**TABLES PRIMAIRES**

>**Table USER**

| Champ | Type | Spécificités | Description |
|-|-|-|-|
|id|INT| PRIMARY_KEY / NOT_NULL / AUTO_INCREMENT / UNSIGNED| Id de l'utilisateur|
|username|VARCHAR (64)| NOT_NULL / UNIQUE |
|email|VARCHAR (64)|NOT_NULL / UNIQUE |
|firstname|VARCHAR (64)|NOT_NULL|
|lastname|VARCHAR (64)|NOT_NULL|
|age|TINYINT|NOT_NULL|
|description|TEXT|NULL|
|gender_id|INT|NOT_NULL / FOREIGN_KEY / UNSIGNED|
|user_image|VARCHAR (255)|NULL|
|created_at|TIMESTAMP| NOT_NULL / CURRENT_TIMESTAMP
|updated_at|TIMESTAMP| NOT_NULL / CURRENT_TIMESTAMP
<br/>

>**Table FLAW**

| Champ | Type | Spécificités | Description |
|-|-|-|-|
|id|INT| PRIMARY_KEY / NOT_NULL / AUTO_INCREMENT / UNSIGNED| Id du défaut|
|name|VARCHAR (64)|NOT_NULL / UNIQUE |
|description|VARCHAR (255)|NULL|
|image|VARCHAR (255)|NOT_NULL|
|created_at|TIMESTAMP|NOT_NULL / CURRENT_TIMESTAMP
|updated_at|TIMESTAMP|NOT_NULL / CURRENT_TIMESTAMP

<br/>

>**Table GENDER** 

| Champ | Type | Spécificités | Description |
|-|-|-|-|
|id|INT| PRIMARY_KEY / NOT_NULL / AUTO_INCREMENT / UNSIGNED| Id du genre|
|name| VARCHAR (64)|NOT_NULL / UNIQUE |
|description| VARCHAR (255)|NULL|
|image| VARCHAR (255)|NOT_NULL|
|created_at| TIMESTAMP|NOT_NULL / CURRENT_TIMESTAMP
|updated_at| TIMESTAMP|NOT_NULL / CURRENT_TIMESTAMP

<br/>

---
---
**TABLES ASSOCIATIVES**
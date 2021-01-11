# Dictionnaire de données "Adopte un défaut"

**TABLES PRIMAIRES**

>**Table USER**

| Champ | Type | Spécificités | Description |
|-|-|-|-|
|id|INT| PRIMARY_KEY / NOT_NULL / AUTO_INCREMENT / UNSIGNED| Id de l'utilisateur|
|username|VARCHAR (64)| NOT_NULL / UNIQUE | Username de l'utilisateur|
|email|VARCHAR (64)|NOT_NULL / UNIQUE | Email de l'utilisateur|
|firstname|VARCHAR (64)|NOT_NULL| Prénom de l'utilisateur|
|lastname|VARCHAR (64)|NOT_NULL| Nom de famille de l'utilisateur |
|age|TINYINT|NOT_NULL| Âge de l'utilisateur |
|description|TEXT|NULL| Description de l'utilisateur |
|gender_id|INT|NOT_NULL / FOREIGN_KEY / UNSIGNED| Genre de l'utilisateur (Homme, Femme, Autre)|
|user_image|VARCHAR (255)|NULL| Image de profil de l'utilisateur
|created_at|TIMESTAMP| NOT_NULL / CURRENT_TIMESTAMP | Date de création du profil | 
|updated_at|TIMESTAMP| NOT_NULL / CURRENT_TIMESTAMP | Date de mise à jour du profil |
<br/>

>**Table FLAW**

| Champ | Type | Spécificités | Description |
|-|-|-|-|
|id|INT| PRIMARY_KEY / NOT_NULL / AUTO_INCREMENT / UNSIGNED| Id du défaut|
|name|VARCHAR (64)|NOT_NULL / UNIQUE | Nom du défaut |
|description|VARCHAR (255)|NULL| Description du défaut |
|image|VARCHAR (255)|NOT_NULL| Image représentative du défaut |

<br/>

>**Table GENDER** 

| Champ | Type | Spécificités | Description |
|-|-|-|-|
|id|INT| PRIMARY_KEY / NOT_NULL / AUTO_INCREMENT / UNSIGNED| Id du genre|
|name| VARCHAR (64)|NOT_NULL / UNIQUE | Nom du genre |
|description| VARCHAR (255)|NULL| Description du genre |
|image| VARCHAR (255)|NOT_NULL| Image représentative du genre |

<br/>

---
---
**TABLES ASSOCIATIVES**
# e-Sathi APIs
  e-Sathi API allows you to retrieve informations via GET request and supports the following parameters:

# Documentation

|Field     |	Description  |	
| ------------- | ------------- | 
|get |	This parameter specify the type of the query: users, pages and groups |
||        - users is for user profile informations|
||        - pages is for pages informations|
||        - groups is for groups informations | 
|query |	The query string |	

## Get Users
Allow you to fetch the user information

Example of requests:
[GET] https://e-sathi.com/api.php?get=users&query=USERNAME

[{"user_id":"33","user_name":"skk","user_firstname":"Santosh","user_gender":"male","user_picture":"https:\/\/s3.eu-central-1.amazonaws.com\/e-sathi\/uploads\/photos\/2017\/11\/e-sathi_3cbb081b51bda81371e27b1776fcd971.jpg","user_cover":"photos\/2018\/03\/e-sathi_055caaecc3772913e5616531c367f6fc.jpg","user_registered":"2017-11-25 08:59:07","user_verified":"1"}}]

Structure of response:
[user_id] => 1
[user_name] => SKK
[user_fullname] => Chief Happiness Officer
[user_gender] => male
[user_picture] => https:\/\/s3.eu-central-1.amazonaws.com\/e-sathi\/uploads\/photos\/2017\/11\/e-sathi_3cbb081b51bda81371e27b1776fcd971.jpg
[user_cover] =>
[user_registered] => 2017-11-25 08:59:07
[user_verified] => 1

First Create the table in dynamoDB

Create one function in Lambda function
Select the fuction url in advance setting (select the none option for auth type)
Allow all the origin and update the cors policy in (function/function-name/configuration/function-url/edit/advance-setting) add * in headers and methods
Add the permission for dynamoDB table as IAM user(click on configuration/permissions/role-name/policy-name/edit/visual/add-more-permission/search dynamodb/select  all dynamoc permision/select all resource/save-changes)
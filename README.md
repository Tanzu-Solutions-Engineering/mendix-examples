# mendix-examples

## company-expenses on MySQL

````
cd company-expenses
cf create-service p-mysql 100mb company-expenses-mysql
cf push -f manifest-mysql.yml
````

## employee-directory on MySQL

````
cd employee-directory
cf create-service p-mysql 100mb employee-directory-mysql
cf push -f manifest-mysql.yml
````


# Go CRUD
Allows you to create an employee table using go and sql

## Usage

In order to use this app you will first have to create a .env file in the root of the directory with the following variables:

```
DB_DRIVER = databasedriver
DB = databasename
DB_USER = databaseuser
DB_PASSWORD = databasepassword
```

You will also have to install these packages:

```
github.com/joho/godotenv
github.com/go-sql-driver/mysql
```

Then you will run this command in your terminal:

```
go run main.go
```
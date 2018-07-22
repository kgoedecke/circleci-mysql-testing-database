# CircleCI 2.0 MySQL Test Database
This example shows how to deploy a MySQL database along with Apache and PHP for testing purposes during the deployment process. Uses [CircleCI 2.0](https://circleci.com/docs/2.0/). 

# Overview
- Starts a MySQL database along Apache accessible from `localhost`
- Imports a SQL dump file for testing purposes
- MySQL 5.6 and PHP 7.1

# Usage
1. Change `MYSQL_ROOT_PASSWORD`, `MYSQL_DATABASE`, `MYSQL_USER` and `MYSQL_PASSWORD` in `config.yml`
2. Place your SQL dump in `/sql-data/` and change the filename in `config.yml`
3. That's it, you can now run test against a MySQL database running on `localhost:3306`

Enjoy 🚀

# License
MIT

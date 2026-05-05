# MySQL User Management

## Create User
CREATE USER 'newuser'@'localhost' IDENTIFIED BY 'password';

## Grant Privileges
GRANT ALL PRIVILEGES ON mydb.* TO 'newuser'@'localhost';

## Revoke Privileges
REVOKE ALL PRIVILEGES ON mydb.* FROM 'newuser'@'localhost';

## Result
User created and privileges managed successfully.

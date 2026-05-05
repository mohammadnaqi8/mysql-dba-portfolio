
# MySQL Installation on Linux

## Objective
To install and configure MySQL on a Linux server.

## Steps

### 1. Update system
sudo apt update

### 2. Install MySQL
sudo apt install mysql-server -y

### 3. Start MySQL
sudo systemctl start mysql

### 4. Enable MySQL on boot
sudo systemctl enable mysql

### 5. Secure installation
sudo mysql_secure_installation

## User Creation

CREATE USER 'testuser'@'localhost' IDENTIFIED BY 'password';
GRANT ALL PRIVILEGES ON *.* TO 'testuser'@'localhost';

## Result
MySQL installed and configured successfully.

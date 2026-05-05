# MySQL Backup and Restore

## Objective
To perform database backup and restore using mysqldump.

## Backup Command
mysqldump -u root -p mydb > backup.sql

## Restore Command
mysql -u root -p mydb < backup.sql

## Automation Script

#!/bin/bash
DATE=$(date +%F)
mysqldump -u root -p mydb > backup_$DATE.sql

## Result
Backup and restore completed successfully.

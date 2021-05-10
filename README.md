# MYSQL-Errors

### Error: 13 (Permission denied)
```
Permisson errors:
$service mysql status
MYSQL
# chown mysql:adm /var/log/mysql/error.log
# chown mysql:adm /var/log/mysql
# chown root:syslog /var/log
# chown root:root /var
# chmod 0640 /var/log/mysql/error.log
# chmod 0750 /var/log/mysql
# chmod 0775 /var/log
# chmod 0755 /var
MARIA DB
# chown mysql:adm /var/log/mariadb/mariadb.log
# chown mysql:adm /var/log/mariadb/
# chown root:root /var/log/
# chown root:root /var
# chmod 0640 /var/log/mariadb/mariadb.log
# chmod 0750 /var/log/mariadb/
# chmod 0775 /var/log/
# chmod 0755 /var
```
### Space Error
```
purge or delete
/var/lib/mysql/binlog.***

causing huge file of sql schema.
```
### Configuration Errors
```
Check configs erros
$service mysql status
$journalctl  -b 0 -u mysql
```

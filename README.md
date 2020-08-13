# docker-mysql8-go


# access mysql container from host with pass
mysql -u ${DB_USER} -p -h localhost -P ${DB_PORT} --protocol=tcp


## debian buster mysql-client
apt update
apt install default-mysql-client
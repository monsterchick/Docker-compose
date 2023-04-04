docker-compose up -d

# access mysql
mysql -u example_user -pexample_password -h localhost -P 3306 example_db_name

docker-compose down

docker-compose up -d

docker inspect -f '{{range .NetworkSettings.Networks}}{{.IPAddress}}{{end}}' home_wordpress_1    # get ip of a container by input container_id

mysql -h localhost -P 3306 -u example_user -p    # access mysql    # not work

docker-compose down

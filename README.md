# LAMP-03
start with nothing
-----------------------


this creates a database:
started from lamp04:

docker run --name some-mysql -e MYSQL_ROOT_PASSWORD=my-secret-pw -d mysql:latest

docker exec -it some-mysql mysql -u root -p

(password is my-secret-pw)

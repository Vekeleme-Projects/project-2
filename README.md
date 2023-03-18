![aws-lift-and-shift drawio (6)](https://user-images.githubusercontent.com/74677661/225818449-73cc5be3-3d16-439e-bdf1-d6e67ca12093.png)


# Prerequisites
#
- JDK 1.8 or later
- Maven 3 or later
- MySQL 5.6 or later

# Technologies 
- Spring MVC
- Spring Security
- Spring Data JPA
- Maven
- JSP
- MySQL
# Database
Here,we used Mysql DB 
MySQL DB Installation Steps for Linux Centos 7:
- $ sudo yum update -y
- $ sudo yum install mariadb-server -y

Then look for the file :
- /src/main/resources/accountsdb
- accountsdb.sql file is a mysql dump file.we have to import this dump to mysql db server
- > mysql -u <user_name> -p accounts < accountsdb.sql

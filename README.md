![aws-beanstalk drawio (1)](https://user-images.githubusercontent.com/74677661/226123402-19e0e372-76fe-4310-98be-f631ed0983c5.png)


# Prerequisites
#
- JDK 1.8 or later
- Maven 3 or later

# AWS Services 
#
- Route 53
- CloudFront
- Elastic LoadBalancer (Application Loadbalancer)
- Elastic Beanstalk
- CloudWatch
- AutoScaling Group
- Acitive MQ (Memcached 1.4)
- ElastiCache
- S3 Bucket
- Amazon RDS

# Technologies 
- Spring MVC
- Spring Security
- Spring Data JPA
- Maven
- JSP


Initialize Amazon RDS using the file below:
- /src/main/resources/accountsdb
- accountsdb.sql file is a mysql dump file.we have to import this dump to mysql db server
- > mysql -h <RDS endpoint> -u <user_name> -p accounts < accountsdb.sql

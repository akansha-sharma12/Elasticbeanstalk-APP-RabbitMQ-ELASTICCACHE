# Prerequisites
#
- JDK 11 
- Maven 3 
- MySQL 8

# Technologies 
- Spring MVC
- Spring Security
- Spring Data JPA
- Maven
- JSP
- Tomcat
- MySQL
- Memcached
- Rabbitmq
- ElasticSearch
# Database
Here,we used Mysql DB 
sql dump file:
- /src/main/resources/db_backup.sql
- db_backup.sql file is a mysql dump file.we have to import this dump to mysql db server
- > mysql -u <user_name> -p accounts < db_backup.sql

### :globe_with_meridians: AWS Elastic Beanstalk Web Application Deployment (Tomcat | Scalable Architecture)

*Description:

Deployed a scalable and fault-tolerant **Java-based web application** on **AWS Elastic Beanstalk**, utilizing a managed **Tomcat** environment. The project demonstrates automated provisioning, deployment, and scaling of a dynamic website with complete AWS integration — from DNS routing to database management and monitoring.

*Architecture Overview:

**Hosting Platform:** AWS **Elastic Beanstalk** managing Tomcat application servers with **auto-scaling** and **load balancing** for high availability.
*Frontend Access:

**Amazon Route 53** used for domain management and DNS routing.
**Amazon CloudFront** configured as a CDN to deliver website content with low latency.

*Application Deployment:

Application artifacts stored in **Amazon S3** and deployed automatically to Beanstalk instances.
**Elastic Load Balancer (ALB)** distributes incoming traffic across instances for reliability.
*Backend Integration:

**Amazon RDS (MySQL)** used for relational database management.
**Memcached** integrated for caching to optimize performance.
**Amazon MQ** used for message queuing between application components.
*Monitoring & Logging:

**Amazon CloudWatch** monitors application performance and instance health metrics.
Auto-scaling policies trigger new instance launches during high traffic.

*Key Technologies:

AWS Elastic Beanstalk, Apache Tomcat, Amazon S3, Amazon RDS (MySQL), Amazon Route 53, Amazon CloudFront, Amazon MQ, Amazon CloudWatch, Memcached, Elastic Load Balancer, Auto Scaling


<img width="1774" height="1024" alt="Screenshot 2025-09-20 at 2 14 17 AM" src="https://github.com/user-attachments/assets/160358a5-d934-4207-bc70-3e296ada2a8e" />




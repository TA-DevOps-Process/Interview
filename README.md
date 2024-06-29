# Welcome to our comprehensive list of interview questions designed to assess your skills and suitability for DevOps Engineer.

These questions cover a range of topics from technical expertise to problem-solving abilities. Get ready to showcase your knowledge and demonstrate why you're the perfect fit for our team. 

**Time Allotted  : 1.15 hr**

Good luck!

You will receive the **IP address, username, and password** of the instance separately.

## a) Basic Linux Commands:

Collect the following details from the aws server shared to you:

1. Server's operating system version
2. Disk space availability
3. RAM usage
4. CPU cores and speed
5. CPU architecture
6. Number of users currently logged in
7. Instantaneous load (refreshed every 2 seconds)
8. PID of the process using port 22
9. List of services in LISTEN status

## b) Identify and resolve any Nginx website-related issues through troubleshooting and debugging.

Detect and address Nginx website issues by troubleshooting and debugging potential configuration and performance issues. Accessing the website should be possible both via its IP address and by appending "/web".

e.g: <ip-of-instance>/web

## c) Create a shell script that backups the MySQL database and includes steps for uploading a file to AWS S3 and validating its presence in the appropriate bucket.


Complete the script by incorporating the procedure to backup the database and upload the backup file to the S3 bucket titled "tadevops--db--backup".

S3 bucket : **tadevops--db--backup**

Shell script to get DB details:

```javascript
#!/bin/bash

# Variable definition for DB backup

DB_NAME="devops_db"
DB_USER="root"
DB_HOST="localhost"
```

## d) Craft a Terraform script to generate an EC2 instance and showcase its public IP address as part of the Terraform output. You can use Terraform Registry for 15 min.

## e) Create an architectural blueprint for hosting a Frontend application on AWS while prioritizing strong security measures.
This exercise evaluates your capability to analyze requirements and devise a solution, showcasing your problem-solving skills essential for real-world scenarios. Cost and security suggestions are anticipated. **This segment involves only discussion, and actual implementation is not within the scope.**

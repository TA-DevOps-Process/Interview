# Welcome to our comprehensive list of interview questions designed to assess your skills and suitability for DevOps Engineer.

These questions cover a range of topics from technical expertise to problem-solving abilities. Get ready to showcase your knowledge and demonstrate why you're the perfect fit for our team. 

**Time Allotted  : 1hr**

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

## b) Scripting:
There are two questions of which **only one** needs to be solved.

Create a Terraform script to set up an S3 bucket with **versioning**, **object locking**, and an **attached bucket policy**. Ensure the script also **outputs the bucket's domain name**. You are allowed to use terraform registry for a period of 15 min.


or 

Develop a shell script to produce 10 files, each named, for instance: TA-Manager-1.txt to TA-Manager-10.txt and TA-employee-1.txt to TA-employee-10.txt. Sort the files listed under the directory, then move the files ending with "Manager" to a separate directory, and list the remaining files that were not copied from the directory.

## c) Docker:

Compose a Dockerfile for streamlining the execution of a JavaScript file. 
Prior to dockerization, ensuring the installation of dependencies like Node is crucial. The command for installing Node is **npm install express**, and the command to execute the app is **node app.js**.
#### Content of app.js

```javascript
const express = require('express')
const app = express()
const port = 3000

app.get('/', (req, res) => {
  res.send('DevOps!')
})

app.listen(port, () => {
  console.log(`Your Sample app listening on port ${port}`)
})
```

## d) Jenkins:

Create and implement a declarative Jenkins pipeline to build the Docker image mentioned above and deploy it as a container on the instance provided. The IP address of the Jenkins server will be shared seperately.
```javascript
DockerHUb login
Username: tadevops24
Password: TaDevOps@$24

Repository : tadevops24/devops
Jenkins URL: http://<ip-of-jenkins-server>:8080/
Jenkins username: tadevops24
Jenkins password: TaDevOps@$24
```

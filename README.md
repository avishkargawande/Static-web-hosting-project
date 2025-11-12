
#  Deploy My Own static website
## Introduction

In this project we learn about how to deploy static website on Amazon-Linux Ec2 instatnce using a
 webserver like Apache(httpd) and Nginx.
##  Features

* Host static HTML files on an Amazon Linux EC2 instance
* Publicly accessible via the instance’s public IP
* Secure access with Security Groups
* Lightweight and cost-effective hosting
##  Prerequisites

* AWS account
* Luanch Amazon-linux Ec2 instance
* Puplic and Private key with .pem extention
* Security groups which allows HTTP(80) and SSh(22) ports.
##  Steps to deploy website

**1.** Launch EC2 Instance-
[![Screenshot-7.png](https://i.postimg.cc/rF0W2DtL/Screenshot-7.png)](https://postimg.cc/BX3txQgh)



**2.** Connect to EC2

[![Screenshot-9.png](https://i.postimg.cc/7ZrCvmkg/Screenshot-9.png)](https://postimg.cc/TpQ2gjhw)


**3.** Update Packages and Install nginx Web Server.

[![Screenshot-2025-08-23-144526.png](https://i.postimg.cc/gks05dgP/Screenshot-2025-08-23-144526.png)](https://postimg.cc/XpZ3BMM2)

**4.** Start & Enable nginx and check the status of webserver
[![Screenshot-2025-08-23-144601.png](https://i.postimg.cc/4Nffpqs2/Screenshot-2025-08-23-144601.png)](https://postimg.cc/14d1QWgD)

 **5.**Go to your folder and open file with vim editor

 [![Screenshot-2025-08-23-150844.png](https://i.postimg.cc/kGVyHfd0/Screenshot-2025-08-23-150844.png)](https://postimg.cc/30Tp4jN1)

**6.** Test Website(Open browser and visit with Public IP address)

[![Screenshot-2025-08-23-153047.png](https://i.postimg.cc/fLYdSpDT/Screenshot-2025-08-23-153047.png)](https://postimg.cc/Kkvjd91d)

**7.** See your website in browser

[![Screenshot-2025-08-23-150753.png](https://i.postimg.cc/xjtCpnxV/Screenshot-2025-08-23-150753.png)](https://postimg.cc/py5RpbMs)



##  Summary

 This project shows how to deploy a static website on an Amazon Linux EC2 instance using nginx.
 It covers how to launch an EC2 instance, installing a web server, uploading website files, and accessing the site
 via the public IP.
 Simple, fast, and cost-effective static hosting on AWS.
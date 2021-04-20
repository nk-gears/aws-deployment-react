# Boilerplate React App
This project demonstrates integration between Github Actions and AWS Elastic Beanstalk service.

# Application Details
Simple React Application created using create-react-app

# Automation Steps
* Github Action API call into AWS Service
* Auto provision of AWS EC2 Instance 
* Auto creation of AWS S3 Bucket for service
* Auto creation of AWS Security groups and roles
* Auto creation of AWS Application Load Balancers
* Auto Build of specified NodeJS (AWS Variant) Docker image from AWS ECR
* Build Application in the specified container
* Exposing ports to open world on Edge Servers
* Route53 Integration possible if needed
* Auto Backup provisioning can be intergrated with S3 Glacier if needed

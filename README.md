# This is for the project to create a website using AWS, Python, Java, and SQL.
blog: https://medium.com/@renrihui8415/7-aws-cloud-architecture-building-using-terraform-03-ec2-fleet-asg-tf-ca2303ed8a19
# Architecture overview

Please refer to _Architecture_Diagram_Website_with_AWS.png

# aws-website building
Overview:
This repository provides to create a well-architected, secure and efficient cloud infrastructure using Terraform (Infrastructure as Code).

Terraform helps to achieve a fully automated process by uploading and building website resources based on all shared files in repositories of:
    1. Terraform-Project-Website-AWS (Architecture)
    2. SQL-StoredProcedure-Project-Website-MySQL (Backend Database and Data Analysing)
    3. Python-Project-Website-Lambda (Computation)
    4. DockerImage-Project-Website (Container)
    5. Java-html-Project-Website (Frontend Website)

Specifically in this repo:
The website is built with AWS resources (VPC, ALB, Route53, ASG, S3, RDS, ECS, Lambda, EC2, Cloudfront, ACM, WAF, SQS, SNS, CloudWatch, IAM...).


## Requirements

* AWS CLI (with at least one profile)
* Terraform (website building automation)
* Python (Lambda Function automation)

## Deploying

terraform init
terraform validate
terraform plan
terraform apply
terraform destroy

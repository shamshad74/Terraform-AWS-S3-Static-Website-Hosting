# Terraform-AWS-S3-Static-Website-Hosting

## Project Description:
In this project, I developed a streamlined infrastructure for hosting a static website using Terraform and Amazon Web Services (AWS) S3. The primary goal of this project is to demonstrate the automated provisioning and deployment of a web hosting solution for static websites.

## Overview:

![Screenshot 2024-02-13 130224](https://github.com/shamshad74/Terraform-AWS-S3-Static-Website-Hosting/assets/117065471/b972f1a1-8f9e-4d86-ae8e-d7115a703bd5)

## Key Components and Features:

### Terraform Infrastructure as Code (IaC):

I utilized Terraform, an IaC tool, to define and provision the AWS resources required for my static website hosting solution. This allows for version-controlled, repeatable infrastructure deployments.

### AWS S3 Bucket:

I created an S3 bucket to store and serve the static website files. This bucket is configured for website hosting, allowing for easy content delivery.

### Content Upload and Management:

I provided instructions and scripts for uploading and managing my website content within the S3 bucket.

## Prerequisites:
1. Basic knowledge of AWS services and concepts.
2. Familiarity with Terraform and infrastructure as code principles.
3. An AWS account with appropriate permissions.
4. An IDE of your Choice , I would suggest VS Code Editor .
5. This project serves as an excellent foundation for hosting various types of static websites, including personal blogs, portfolio sites, or small business websites.


## Steps :

### Step 1: Set Up Your Development Environment

Install Terraform and the AWS Command Line Interface (CLI) on your local machine. Configure your AWS credentials by running ``` aws configure ``` and providing your AWS access key and secret key.

### Step 2: Define Your Website Content

To prepare static website files (HTML), place them in the directory where your Terraform configuration files are located. Name the main HTML file "index.html," and optionally, you can also include an "error.html" file. If you prefer, you can reference my repository for the static website HTML files.

### Step 3: Terraform Configuration File Syntax

If we want to Create a terraform configuration file we have to use .tf (e.g., main.tf) to define the infrastructure as code using terraform.

### Step 4: Define your Configuration Files in your IDE

### Define the AWS provider and required resources like S3 buckets, IAM roles, and policies

1.Define ``` provider.tf ``` file using the below code :
```
provider "aws" {
    region = "ap-south-1"
}
































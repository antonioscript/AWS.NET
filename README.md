# AWS.NET

Repository created to organize .NET applications using AWS services.

---

## Compute Essentials

### 🔗 **Lambda**
- [Lambda Function with .NET](https://github.com/antonioscript/AWS.Lambda.NET)  
  Example of a serverless function using AWS Lambda with .NET.

- [Hosting .NET API on AWS Lambda](https://github.com/antonioscript/API.NET.AWS.Lambda)  
  .NET API hosted on AWS Lambda using API Gateway.

### 🔗 **ECS**
- [Simple API Project on ECS](https://github.com/antonioscript/API.NET.SimpleCluster.ECS)</br>
  Simple API hosted on ECS + Fargate
  
- [API .NET hosted on ECS](https://github.com/antonioscript/API.NET.AWS.ECS)</br>
.NET API with MongoDB, running on an AWS ECS Fargate cluster.

### 🔗 **EC2**
- [API .NET hosted on EC2](https://github.com/antonioscript/API.NET.AWS.EC2)  
  Example of a .NET application running on an EC2 instance.


---

## Serverless Essentials

### 🔗 **API Gateway**
- [API Gateway](https://github.com/antonioscript/AWS.APIGateway.NET)  
  This repository demonstrates how to integrate Amazon API Gateway with .NET applications.

---

## Storage Essentials

### 🔗 **S3**
- [API .NET with S3 integration](https://github.com/antonioscript/API.NET.AWS.S3)  
  .NET API to perform operations with Amazon S3 (upload, download, list files, etc.).

---

## Networking Essentials

### 🔗 **VPC**
- [AWS VPC](https://github.com/antonioscript/AWS.VPC)  
  Theoretical repository on how VPC works

---

### 🔗 **Route 53**
- [Route 53](https://github.com/antonioscript/AWS.Route53)  
  This repository showcases how to use Amazon Route 53 for DNS management on AWS.

---

## Security Essentials

### 🔗 **IAM**
- [AWS IAM](https://github.com/antonioscript/AWS.IAM)  
  This repository provides a focused overview of AWS Identity and Access Management (IAM).


---

### 🔗 **Amazon Cognito**
- [Amazon Cognito](https://github.com/antonioscript/AWS.Cognito.NET)  
  Example of integrating Amazon Cognito with .NET for user authentication and authorization.

---

## Monitoring Essentials

### 🔗 **CloudWatch**
- [AWS CloudWatch](https://github.com/antonioscript/AWS.CloudWatch)  
  API created in . NET driving logs in Serilog with Cloud Wacth

---


# Configuration Environment (Visual Studio)

## Install Amazon CLI
https://docs.aws.amazon.com/cli/latest/userguide/getting-started-install.html

### Login CLI
``` powersehl
aws configure --profile aws-admin
```
![image](https://github.com/user-attachments/assets/0853554a-bdc1-47dc-9fe7-e39bd98f0453)

### Test to see if it worked
``` powershel
aws sts get-caller-identity --profile aws-admin
```

### Entension VS 2022

![image](https://github.com/user-attachments/assets/bc0c777c-88bd-40af-9bb9-da0ca6900e00)
https://marketplace.visualstudio.com/items?itemName=AmazonWebServices.AWSToolkitforVisualStudio2022

### Templates AWS
```powershel
dotnet new -i Amazon.Lambda.Templates
```


## References

https://codewithmukesh.com/blog/essential-aws-services-for-dotnet-developers/


# AWS.NET

Repository created to organize .NET applications using AWS services.

---

## Compute Essentials

### 🔗 **Lambda**
- [Lambda Function with .NET](https://github.com/antonioscript/AWS.Lambda.NET)  
  Example of a serverless function using AWS Lambda with .NET.

- [Hosting .NET API on AWS Lambda](https://github.com/antonioscript/API.NET.AWS.Lambda)  
  .NET API hosted on AWS Lambda using API Gateway.

### 🔗 **EC2**
- [API .NET hosted on EC2](https://github.com/antonioscript/API.NET.AWS.EC2)  
  Example of a .NET application running on an EC2 instance.

---

## Storage Essentials

### 🔗 **S3**
- [API .NET with S3 integration](https://github.com/antonioscript/API.NET.AWS.S3)  
  .NET API to perform operations with Amazon S3 (upload, download, list files, etc.).

---



-----
## SQS
https://github.com/antonioscript/AWS.Lambda.NET

## API Gateway
https://github.com/antonioscript/AWS.Lambda.NET

## DynamoDB
https://github.com/antonioscript/AWS.Lambda.NET

## EC2
https://github.com/antonioscript/API.NET.AWS.EC2

## Configuration Environment (Visual Studio)

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



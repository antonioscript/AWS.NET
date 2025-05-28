# AWS.NET
Repository created to organize .NET applications using AWS services

## Host API .NET on Lambda AWS
https://github.com/antonioscript/API.NET.AWS.Lambda

## Lambda (Function)
https://github.com/antonioscript/AWS.Lambda.NET

## SQS
https://github.com/antonioscript/AWS.Lambda.NET

## API Gateway
https://github.com/antonioscript/AWS.Lambda.NET

## DynamoDB
https://github.com/antonioscript/AWS.Lambda.NET

## S3
https://github.com/antonioscript/API.NET.AWS.S3

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



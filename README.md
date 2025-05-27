# AWS.NET
Repository created to organize .NET applications using AWS services

## Lambda
https://github.com/antonioscript/AWS.NET.Lambda

## API Gateway
https://github.com/antonioscript/AWS.NET.Lambda

## DynamoDB
https://github.com/antonioscript/AWS.NET.Lambda


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



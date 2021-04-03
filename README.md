# pets-stepfunction


## Create AWS API Gateway
https://www.youtube.com/watch?v=R1s7Hi3DH7Y

## Initilize a step function
```bash
(base) ~/repo/personal-github  $ sam init
Which template source would you like to use?
	1 - AWS Quick Start Templates
	2 - Custom Template Location
Choice: 1
What package type would you like to use?
	1 - Zip (artifact is a zip uploaded to S3)
	2 - Image (artifact is an image uploaded to an ECR image repository)
Package type: 1

Which runtime would you like to use?
	1 - nodejs14.x
	2 - python3.8
	3 - ruby2.7
	4 - go1.x
	5 - java11
	6 - dotnetcore3.1
	7 - nodejs12.x
	8 - nodejs10.x
	9 - python3.7
	10 - python3.6
	11 - python2.7
	12 - ruby2.5
	13 - java8.al2
	14 - java8
	15 - dotnetcore2.1
Runtime: 2

Project name [sam-app]: pets-stepfunction

Cloning app templates from https://github.com/aws/aws-sam-cli-app-templates

AWS quick start application templates:
	1 - Hello World Example
	2 - EventBridge Hello World
	3 - EventBridge App from scratch (100+ Event Schemas)
	4 - Step Functions Sample App (Stock Trader)
	5 - Elastic File System Sample App
Template selection: 4

-----------------------
Generating application:
-----------------------
Name: pets-stepfunction
Runtime: python3.8
Dependency Manager: pip
Application Template: step-functions-sample-app
Output Directory: .

Next steps can be found in the README file at ./pets-stepfunction/README.md
```

## Add deployment configurations


## Build pets step function 

```bash
sam build 
```

## Test step function locally with AWS CLI



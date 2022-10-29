# aws-serverless
### Description
Introduce a common design pattern of AWS Serverless Services

### Architecture
![aws-serverless](https://user-images.githubusercontent.com/31915035/198856187-e84a1fa1-27ff-40c9-b54f-39278e9e2f09.png)


### Services Used
- [S3 - Server Static App](https://aws.amazon.com/s3/?nc2=h_m1)
- [API Gateway - REST API](https://aws.amazon.com/api-gateway/?nc2=h_m1)
- [Lambda - Execute Code on Demand](https://aws.amazon.com/lambda/?nc2=h_m1)
- [DynamoDB - Store & Retrieve Data](https://aws.amazon.com/dynamodb/?nc2=h_m1)
- [Cognito - Authentication](https://aws.amazon.com/cognito/?nc2=h_m1)
- [Route53 - Translate URL](https://aws.amazon.com/route53/?nc2=h_m1)
- [CloudFront - Faster Delivery](https://aws.amazon.com/cloudfront/?nc2=h_m1)

### API Gateway
Handles Request-Response Cycle

| Method | Endpoint      | Description |
| ----------- | -----------|----------- |
| POST | /sample-endpoint     | Add Data       |
| GET | /sample-endpoint   | Get Data        |
| DELETE | /sample-endpoint   | Remove Data        |

### Lambda
1. Connecting Lambda Functions to API Gateway Endpoints
2. Editing Lambda handler function
### Data Storage with DynamoDB
1. Creating a Table in DynamoDB
2. Connecting Lambda Functions with DynamoDB

### Authentication with Cognito
1. Creating a Cognito User Pool
2. Adding Cognito to a Frontend App
3. Using a Cognito Authorizer with API Gateway

### Content Delivery & Hosting with S3, CloudFront and Route53
1. Creating a S3 Bucket
2. Setting up a CloudFront Distribution
3. Registering and Connecting a Domain to the CloudFront Distribution

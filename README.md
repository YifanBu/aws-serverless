# aws-serverless
### Description
Introduce a common design pattern of AWS Serverless Services

### Architecture
https://github.com/YifanBu/aws-serverless/blob/078a8aae7bd3daddc42722c1278d7ae40666afc3/aws-serverless.png

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


### Data Storage with DynamoDB


### Authentication with Cognito


### Content Delivery & Hosting with S3, CloudFront and Route53
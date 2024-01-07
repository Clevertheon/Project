# REST API Documentation

This repository contains examples and demonstrations related to REST API development, including creating Swagger documentation, building APIs with AWS API Gateway, Express.js, or Python Flask, and executing requests with Postman.

## 1. AWS API Gateway Example

### Basic Configuration and Resource Creation

Follow these steps to create a simple AWS API Gateway with a Lambda function handling requests.

1. **Create AWS API Gateway:**
   - Log in to the AWS Management Console.
   - Go to the API Gateway service.
   - Click on "Create API" and choose "Rest API" type.
   - Enter the API name and create a default route.

2. **Integrate Lambda Function:**
   - In the API Gateway console, select the created API.
   - Go to the "Integrations" section and click "Create".
   - Choose "Lambda Function" as the integration type.
   - Select the Lambda function and set the integration path and resource.

3. **Deploy API:**
   - Go to the "Deployment" section.
   - Create a new deployment stage and deploy the API.

4. **Update Lambda Function Code:**
   - Modify the Lambda function code to accommodate new model object properties.


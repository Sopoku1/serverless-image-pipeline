# Serverless Image Processing Pipeline

## 📸 Overview
A serverless application that resizes images uploaded to S3 using AWS Lambda, Step Functions, and API Gateway.

## 🧱 Architecture
![Architecture Diagram](link-to-diagram)

## 🧰 Prerequisites
- AWS Account
- AWS CLI configured
- Pillow (Python) or sharp (Node.js) Lambda Layer

## 🚀 Deployment Steps
1. Create S3 buckets: `original-images-bucket-xyz`, `resized-images-bucket-xyz`
2. Deploy Lambda function with image library
3. Set up Step Functions state machine
4. Connect API Gateway to Step Functions
5. Test by uploading an image

## 🔗 API Endpoint
`https://your-api-id.execute-api.region.amazonaws.com/prod/resize`

## 📝 License
MIT

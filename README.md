# AWS Serverless Task Manager API

A fully serverless REST API built on AWS using Lambda, API Gateway, and DynamoDB.

## Architecture
![Architecture](architecture/serverless-architecture.png)

## Services Used
- AWS Lambda (Python)
- Amazon API Gateway (REST)
- Amazon DynamoDB
- IAM (role-based access)
- CloudWatch (logging)

## Endpoints

### POST /tasks
Creates a new task.
```json
{
  "title": "Example task"
}

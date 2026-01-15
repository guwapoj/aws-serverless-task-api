# AWS Serverless Task Manager API

A fully serverless REST API built on AWS using Lambda, API Gateway, and DynamoDB.

## Architecture
![Architecture](<img width="621" height="137" alt="serverless-architecture drawio" src="https://github.com/user-attachments/assets/f3777553-a6a8-4fc1-a47f-3813c14445a1" />


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

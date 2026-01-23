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

## Security
- Implemented least-privilege IAM policies restricting Lambda access to specific DynamoDB actions and resources
- Removed managed full-access policies to reduce attack surface
- Validated permissions through functional API testing

## Endpoints

### POST /tasks
Creates a new task.
```json
{
  "title": "Example task"
}

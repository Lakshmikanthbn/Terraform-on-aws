# Serverless Web Application: Feedback Submission and Viewing

## Objective
Build a simple web application that allows users to submit and view feedback. The application is fully serverless, leveraging AWS services to handle the backend logic, data storage, and frontend hosting using Terraform for Infrastructure as Code (IaC).

## AWS Services Used
- **AWS Lambda**: For backend logic.
- **Amazon API Gateway**: For creating APIs.
- **Amazon DynamoDB**: For storing feedback data.
- **Amazon S3**: For hosting the static web application.
- **AWS IAM**: For managing access permissions.
- **Terraform**: For Infrastructure as Code (IaC).

## Project Structure
├── main.tf
├── variables.tf
├── outputs.tf
├── lambda_function.py
├── frontend
│ ├── index.html
│ ├── styles.css
│ └── script.js
├── README.md

## Getting Started

### Prerequisites
- AWS Account
- AWS CLI configured with proper access
- Terraform installed
- Basic knowledge of AWS services and web development



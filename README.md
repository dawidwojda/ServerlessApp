# Serverless App

A production-ready serverless application built on AWS using API Gateway and Lambda, with a lightweight frontend for testing. Infrastructure is managed through Infrastructure as Code (Terraform) and automated CI/CD pipelines.

## Project Overview

This project demonstrates a complete serverless architecture with:
- **Backend**: AWS Lambda functions (Python)
- **API Layer**: AWS API Gateway (REST API)
- **Frontend**: Simple HTML/JavaScript interface for API testing
- **Infrastructure**: Terraform-based IaC for reproducible deployments
- **CI/CD**: Automated deployment pipelines via GitHub Actions

## Project Structure

```
ServerlessApp/
├── backend/          # Lambda function code
├── frontend/         # Web interface for API testing
├── infrastructure/   # Terraform infrastructure definitions
├── docs/             # Project documentation and architecture diagrams
└── README.md
```

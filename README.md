# APIs with Lambda and API Gateway

## Overview

Built a serverless REST API using AWS Lambda and Amazon API Gateway to understand how application layers communicate within a three-tier cloud architecture.

## AWS Services Used

* AWS Lambda
* Amazon API Gateway
* Amazon DynamoDB
* AWS IAM

## Architecture

### API Layer

* Created a REST API using Amazon API Gateway
* Configured API resources and methods
* Deployed the API to a production stage
* Generated Invoke URLs for external access

### Application Logic

* Built an AWS Lambda function to process incoming API requests
* Implemented backend logic to retrieve user data
* Added error handling for invalid requests and missing records

### Data Integration

* Configured Lambda to query DynamoDB records
* Returned structured JSON responses to API consumers

## Key Concepts Practiced

* REST APIs
* API resources and methods
* GET requests
* Lambda proxy integration
* API deployment stages
* Invoke URLs
* API documentation

## Skills Demonstrated

* Serverless architecture
* API development
* Lambda integration
* Backend workflows
* JSON responses
* AWS IAM permissions
* API documentation

## Key Learnings

* How API Gateway acts as the front door for applications
* How Lambda processes API requests
* How backend services communicate with databases
* API deployment and versioning using stages
* Publishing API documentation through API Gateway

## Project Documentation

Detailed project documentation is included in this repository.

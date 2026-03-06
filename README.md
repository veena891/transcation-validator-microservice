Hi, I'm Veena 👋

Software Engineer with experience building scalable backend systems using Java, Spring Boot, and AWS.

Tech Stack
Java | Spring Boot | AWS | Microservices | MongoDB | PostgreSQL | Docker

Projects
• Cloud Student Management System – Spring Boot microservices with AWS RDS and S3
• REST API Microservices Platform – Java backend services with Docker
• AI COVID-19 Detection System – TensorFlow model deployed with AWS Lambda

Currently interested in distributed systems, backend engineering, and scalable cloud platforms.
# Transaction Validator Microservice

A Java Spring Boot microservice that validates financial transactions and ensures data integrity before processing.

## Overview
This microservice provides REST APIs that validate transaction requests based on predefined business rules such as amount validation, required fields, and transaction status checks.

It is designed using a microservices architecture and can be integrated into larger financial or payment systems.

## Tech Stack
Java  
Spring Boot  
REST APIs  
MongoDB / PostgreSQL  
Docker  
Maven  

## Features
• Transaction request validation  
• Input field validation and error handling  
• REST API endpoints for transaction processing  
• Logging and monitoring support  
• Scalable microservice architecture  

## Architecture
Client → REST API → Spring Boot Microservice → Database

## API Example

POST /api/transactions/validate

Example Request
``json
{
  "transactionId": "TXN1001",
  "amount": 250,
  "currency": "USD",
  "status": "PENDING"
}
,,,
{
  "valid": true,
  "message": "Transaction is valid"
},,,

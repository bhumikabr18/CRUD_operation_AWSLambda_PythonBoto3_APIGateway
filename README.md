# CRUD_operation_AWSLambda_PythonBoto3_APIGateway
This project demonstrates a simple CRUD (Create, Read, Update, Delete) operation using AWS Lambda, Python boto3, and API Gateway to manage student data in a DynamoDB table.

# Demonstration Video
https://drive.google.com/file/d/1pcRKtbaQ8P3HDHyVX_XuZ5t-UbuFhcuV/view?usp=drivesdk

# Features
- Create: Add new student records.
- Read: Retrieve details of a specific student or all students.
- Update: Modify existing student information.
- Delete: Remove student records.

# Architecture
1. AWS Lambda: Handles the backend logic for each CRUD operation.
2. DynamoDB: A NoSQL database to store and manage student data.
3. API Gateway: Provides RESTful endpoints to interact with the Lambda functions.

# Technologies Used
- AWS Lambda: For serverless backend processing.
- DynamoDB: To store student data.
- API Gateway: To expose the API endpoints.
- Python boto3: AWS SDK for Python to interact with DynamoDB.

# How It Works
1. API Gateway receives HTTP requests for each CRUD operation.
2. API Gateway triggers the respective Lambda function based on the HTTP method (POST, GET, PUT, DELETE).
3. The Lambda function uses the boto3 library to interact with DynamoDB.
4. DynamoDB stores and retrieves student data as per the request.

# Endpoints
- POST /students_api: Add a new student.
- GET /students_api/{studentId}: Get details of a specific student.
- PUT /students_api/{studentId}: Update a student's information.
- DELETE /students_api/{studentId}: Delete a student.




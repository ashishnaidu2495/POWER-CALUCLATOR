# POWER-CALUCLATOR

The "Powercaluclator" app was developed using several AWS services to ensure efficient functionality and scalability. Below is a list of the AWS services utilized, each with a brief description of their role in the app development.

![Screenshot 2024-08-03 174150](https://github.com/user-attachments/assets/08f90e2c-f213-4214-8124-bffae3370301)
![Screenshot 2024-08-03 174206](https://github.com/user-attachments/assets/d2e92867-f9e8-4534-9df8-31191b6efa07)
![Screenshot 2024-08-03 174224](https://github.com/user-attachments/assets/70d80bc3-5555-472a-aec8-a5733e3f4836)
![Screenshot 2024-08-03 174235](https://github.com/user-attachments/assets/ebd9e07e-421b-4e08-9c4a-01e7e2264252)


## AWS Services Used
  ## AWS Amplify

Purpose: AWS Amplify was used to develop and deploy the front-end of the Power of Math app.
Features: Amplify provides tools to build and manage the app's back-end, along with a powerful CLI for managing resources.
Integration: Simplified integration with other AWS services, allowing for quick setup and configuration.
  
   ## AWS Lambda

Purpose: AWS Lambda was used for executing back-end logic and handling various requests.
Features: Lambda allows the app to run code without provisioning or managing servers, enabling scalable and cost-effective execution.
Integration: Easily triggered by API Gateway, DynamoDB streams, and other AWS services.

  ## Amazon API Gateway

Purpose: API Gateway was employed to create, publish, and manage the API endpoints for the Power of Math app.
Features: Provides a secure and scalable mechanism to expose the app's functionalities via RESTful APIs.
Integration: Directly integrates with AWS Lambda to handle business logic.

   ## Amazon DynamoDB

Purpose: DynamoDB was used as the primary database to store user data and application states.
Features: Offers a fully managed NoSQL database service with fast and predictable performance.
Integration: Seamless integration with AWS Lambda for data processing and API Gateway for data access.

   ## AWS Identity & Access Management (IAM)

Purpose: IAM was utilized to manage user permissions and secure access to AWS resources.
Features: Provides fine-grained access control, ensuring that only authorized users and services have the necessary permissions.
Integration: Used to enforce security policies across all AWS services involved in the app.


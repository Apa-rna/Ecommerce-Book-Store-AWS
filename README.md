This project is an implementation of an Online Book Store using various AWS services and React. With this serverless application, users can conveniently purchase books online. Below are the details of the project setup and implementation steps.
![image](https://github.com/Apa-rna/Ecommerce-Book-Store-AWS/assets/74657132/a16e5cd2-db64-46c2-b73b-6987424d8d07)

Setup
Clone the frontend files required for the application into a local folder.
Open the command line interface in your local machine and navigate to the project folder.
Open the project in Visual Studio Code using the command code ..
Install Amplify globally.
Login into your AWS account.
Create an IAM user named amplify-rohini2 and generate access keys for this user.
Use the generated credentials to login into the IAM User account through the terminal.
AWS Services Used
AWS S3 Storage
AWS Amplify
Cognito User Pool
AWS Lambda
Implementation Steps
Setting up the Project
Clone the frontend files and open them in Visual Studio Code.
Install Amplify globally and login into your AWS account.
Create an IAM user and use its credentials to configure the project.
Adding Authentication with Cognito
Configure Cognito User Pool for authentication.
Creating S3 to Store Images
Set up an S3 bucket to store book images.
Creating Lambda Functions
Create two Lambda functions: processPayment and createOrder to handle book orders.
Adding GraphQL API
Edit schema.graphql and Lambda functions code.
Configure Cloud resources including Userpool, S3 Bucket, AppSync API, DynamoDB Tables, and Lambda Functions.
Running the Application
Install required packages using npm i.
Start the application using npm run start.
Create an admin account and manage book listings.
Configure permissions for users and admins.
Verifying the Order Process
Add books to the cart and proceed to checkout.
Sign in or create a new user account.
Complete the payment process.
Verify the order details in the DynamoDB table.
Hosting the Application
Publish the application to make it available online.
Conclusion
This project demonstrates the implementation of an Online Book Store using various AWS services, providing users with a seamless shopping experience.

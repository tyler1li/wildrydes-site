# Wild Rydes Web Application (Guided AWS Project)

This is a web application for a unicorn ride-sharing service called **Wild Rydes**, based on a tutorial created by "Tiny Technical Tutorials" on YouTube [https://www.youtube.com/watch?v=K6v6t5z6AsU&t=135s&ab_channel=TinyTechnicalTutorials). This project was completed as a hands-on exercise to learn how to build and deploy a full-stack serverless app on AWS using real-world services.

---

## Technologies Used

- **GitHub** – Source code version control and integration with AWS Amplify for CI/CD
- **AWS Amplify** – Frontend hosting and automated deployment from GitHub
- **Amazon Cognito** – User authentication (signup, login, and identity management)
- **API Gateway** – RESTful API entry point
- **AWS Lambda** – Serverless backend functions triggered by API calls
- **Amazon DynamoDB** – NoSQL database for storing ride request data
- **IAM (Identity and Access Management)** – Permission control for accessing AWS services
- **ArcGIS JavaScript API** – Interactive map to allow users to request a ride

---

## How It Works

1. The app is deployed through **AWS Amplify**, which pulls the source code from a connected GitHub repository.
2. When users visit the app, they're prompted to **sign up or log in** via **Amazon Cognito**.
3. After logging in, users can click on a map (powered by ArcGIS) to request a unicorn ride.
4. The **front-end app** sends the ride request to an **API Gateway** endpoint.
5. The request is handled by an **AWS Lambda** function, which stores the ride data in **DynamoDB**.
6. **Amplify’s CI/CD** pipeline automatically deploys updates any time changes are pushed to GitHub.

---

## What I Learned

- How to deploy a serverless web app using **AWS Amplify**
- How to implement **CI/CD** by connecting a GitHub repo to Amplify
- Basic configuration of **Cognito** for secure user authentication
- How **API Gateway** connects frontend requests to **Lambda** functions
- Writing and deploying serverless logic with **Lambda**
- Storing and retrieving structured data using **DynamoDB**
- How IAM roles/policies govern service access and application permissions

---

## Notes

- This project followed the tutorial created by "Tiny Technical Tutorials" on YouTube [https://www.youtube.com/watch?v=K6v6t5z6AsU&t=135s&ab_channel=TinyTechnicalTutorials) and was deployed in my own AWS environment as part of a personal cloud learning initiative.
- All AWS resources have been deleted post-completion.
- No live demo is available. Attached is a file with screenshots and notes taken throughout the process of completing this project.

---

## Acknowledgments

This project is based on the [AWS Serverless Web Application Workshop (Wild Rydes)](https://github.com/aws-samples/aws-serverless-workshops).

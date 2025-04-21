# AWS Serverless API Project (Lab Walkthrough)

This project was completed using AWS Skill Builder. It demonstrates how to deploy a serverless API using Lambda, API Gateway, and S3 — all defined using AWS SAM (Serverless Application Model). Everything was tested and verified through real scenarios in Cloud9.

---

## 🔧 Technologies Used

- AWS Lambda (Python 3.9)
- Amazon API Gateway (HTTP API)
- Amazon S3
- AWS SAM CLI
- Cloud9 IDE
- IAM Roles

---

## ✅ What This Project Does

- Deploys an API endpoint using AWS SAM
- Connects Lambda to read from S3 (`object1`)
- Returns the object content to a browser or curl request

---

## 🧪 How to Test the API

1. Deploy using:

```bash
sam build
sam deploy --guided
curl https://your-api.amazonaws.com/labfunction
{"result": "Welcome to AWS Lambda!"}
---

## 📸 Screenshots (Step-by-Step Walkthrough)

![boto 3](./screenshots/boto 3.png)  
![Browser Contents](./screenshots/Browser Contents.png)  
![Build and Deploy](./screenshots/Build and Deploy.png)  
![Build the Deployment package](./screenshots/Build the Deployment pakage.png)  
![Cloud 9 Terminal](./screenshots/Cloud 9 Terminal.png)  
![Deploy the Application Cloud 9](./screenshots/Deploy the Application Cloud 9.png)  
![Endpoint results verified](./screenshots/Endpoint results verified.png)  
![Lambda S3 Welcome](./screenshots/Lambda S3 Welcome .png)  
![s3bucket access](./screenshots/s3bucket access.png)  
![downloading contents in S3 bucket](./screenshots/downloading contents in S3 bucket.png)  
![successfully Created a stack](./screenshots/successfully Created a stack.png)  
![template.yaml](./screenshots/template.yaml.png)  
![Verified S3 object contents](./screenshots/Verified S3 object contents.png)  
---

## 🧠 Key Takeaways

- Used AWS SAM to deploy a Lambda → API Gateway → S3 architecture
- Understood how templates like `template.yaml` define cloud infrastructure
- Verified S3 content delivery through both curl and browser
- Experienced the real process of provisioning multiple services together

## 🧑🏽‍💻 Author

**Theo7Labs**  
[GitHub](https://github.com/Theo7Labs)


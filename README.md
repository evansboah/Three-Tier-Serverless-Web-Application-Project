# Three-Tier Serverless Web Application on AWS

## 🚀 Project Overview

This project demonstrates how I built a **three-tier serverless web application** using **Amazon S3, CloudFront, API Gateway, Lambda, and DynamoDB**. The goal was to strengthen my AWS skills, gain deeper insights into serverless architecture, and practice integrating multiple services in a production-like environment.

---

## 🔧 Architecture Breakdown

### 1. Presentation Tier

* **Amazon S3**: Hosted the static website (index.html)
* **Amazon CloudFront**: Delivered content globally with caching and improved performance

### 2. Logic Tier

* **AWS Lambda**: Implemented backend logic to process API requests
* **API Gateway**: Exposed REST endpoints to trigger Lambda functions

### 3. Data Tier

* **Amazon DynamoDB**: Stored and retrieved application data efficiently

---

## 🧩 Key Learnings

* Designing **scalable and secure serverless applications**
* Configuring **API Gateway + Lambda** integrations
* Debugging and resolving **CORS issues** between services
* Strengthening skills in **IAM roles, S3 policies, and serverless best practices**

---

## ⚡ Challenges & Solutions

* **Problem**: CORS errors prevented communication between frontend and backend.
* **Solution**: Enabled CORS in API Gateway and added proper response headers in Lambda. Updated `script.js` to include the API invoke URL.

✅ Final result: Verified full connectivity between S3 → CloudFront → API Gateway → Lambda → DynamoDB.

---

## 🎯 Takeaways

This project demonstrates my ability to:

* **Design cloud-native architectures**
* **Troubleshoot cross-service issues**
* **Deploy end-to-end serverless solutions**

---

## 📂 Repository Structure (example)

```bash
├── index.html        # Frontend presentation layer
├── script.js         # API integration logic
├── lambda/           # Lambda function code
├── dynamodb/         # DynamoDB schema and sample data
└── README.md         # Project documentation
```

---

## 🌐 Reference

For more cloud projects and resources, check out: [NextWork Community](https://community.nextwork.org/c/i-have-a-question?automatic_login=true)
# Three-Tier-Serverless-Web-Application-Project

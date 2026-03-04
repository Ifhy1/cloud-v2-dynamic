# Cloud Resume Project v2 - Dynamic Visitor Counter

This project is an evolution of my static resume website. I added a serverless backend to track and display the number of visitors in real-time.

## Architecture
* **Frontend:** HTML/CSS hosted on **Amazon S3** and distributed via **CloudFront**.
* **Database:** **Amazon DynamoDB** stores the visitor count.
* **Backend:** **AWS Lambda** (Python) handles the logic to increment the count.
* **API:** **Amazon API Gateway** acts as the bridge between the website and the Lambda function.

## 🔗 Live Demo
Check it out here: [https://dlnrrz6o74scn.cloudfront.net/v2/index.html] (https://dlnrrz6o74scn.cloudfront.net/v2/index.html)

<h1 align="center">Hi 👋, I'm Salma Mohamed</h1>
<h3 align="center">🌩 Junior Cloud Engineer | AWS Certified | AI & Serverless Enthusiast</h3>

💡 *Aspiring Cloud Engineer passionate about building secure, automated, and AI-integrated solutions on AWS.*

🔭 I’m currently building **AI-powered and serverless solutions** on AWS — focusing on automation, NLP, and cost-efficient architecture using services like Lambda, Polly, Comprehend, and Bedrock.



## 🏅 Certifications

🟧 *AWS Certified Cloud Practitioner*  
 🟨 *AWS Certified Solutions Architect – Associate*


## 🚀 AWS Projects Portfolio
### [🌍 AWS Text Translation App](https://github.com/Salma22C/awsprojects/tree/main/AWS%20Text%20Translation%20App)  
A fully serverless text translation app with a static web UI.  
- **Text Translation API**:
  - Lambda backend using `boto3.translate`  
  - API Gateway exposes `POST /Translator` endpoint  
  - Auto-detects source language and returns translated text  
- **Frontend**:
  - Hosted on S3 (Static Website Hosting)  
  - HTML/JS interface with textarea, dropdown, and fetch call  
- **AWS Services**: Lambda, Amazon Translate, API Gateway, S3  

### [🖼️ AWS S3 Image Thumbnail Generator](https://github.com/Salma22C/awsprojects/tree/main/AutoThumbailGenerator)  
Automatically generates 128x128 thumbnails for images uploaded to S3.  
- **Architecture**:
  - S3 triggers Lambda function on image upload  
  - Pillow (via Lambda Layer) processes the image  
  - Thumbnails saved under `thumbnails/` folder  
- **Security**: IAM roles for Lambda to interact with S3  
- **AWS Services**: S3, Lambda, IAM  

### [🧠 Multilingual Customer Feedback Analyzer](https://github.com/Salma22C/awsprojects/tree/main/Multilingual%20Customer%20Feedback%20Analyzer)  
Serverless system for collecting and analyzing multilingual customer feedback.  
- **Pipeline**:
  - Public API collects feedback  
  - Amazon Translate converts to English  
  - Amazon Comprehend analyzes sentiment  
  - DynamoDB stores data  
  - SNS sends alert if sentiment is negative  
- **AWS Services**: API Gateway, Lambda, Translate, Comprehend, DynamoDB, SNS  

### [🧾 EC2 Monitoring on AWS with Terraform](https://github.com/Salma22C/awsprojects/tree/main/Terraform-EC2-Monitoring)  
Provisions a secure, monitored AWS environment using Terraform.  
- **Infrastructure**:
  - VPC with public/private subnets  
  - EC2 with detailed monitoring  
  - Security Groups with SSH access  
  - VPC Flow Logs via CloudWatch  
  - IAM roles for logging and monitoring  
- **Tools**: Terraform, EC2, VPC, CloudWatch, IAM  


### [🗣 Voice Vault – Text-to-Speech Pipeline](https://github.com/Salma22C/awsprojects/blob/main/Voice%20Vault%20Project)  
Converts long-form `.txt` documents into audio files for video content creation using a fully serverless architecture.  
- **Key Features**:
  - Amazon Polly for speech synthesis  
  - Optional summarization with Amazon Comprehend  
- **AWS Services**: Lambda, S3, Polly, Comprehend, IAM  


### [🤖 Bedrock Code Assistant API](https://github.com/Salma22C/awsprojects/tree/main/Amazon%20Bedrock%20Code%20Assistant%20API)  
Transforms natural language prompts into Python code using Claude Instant via Amazon Bedrock.  
- **Highlights**:
  - First-time use of API Gateway  
  - Demonstrates adaptability in learning new AWS services  
- **AWS Services**: API Gateway, Lambda, Bedrock  



### [📊 FinOps Dashboard – Cost Visualization](https://github.com/Salma22C/awsprojects/tree/main/Serverless%20Data%20Analytics%20and%20Visualization%20Pipeline)  
Built a multi-tier analytics pipeline to visualize AWS cost and usage data.  
- **Tech Stack**:
  - Data cataloging with Glue  
  - Querying with Athena  
  - Visualization with QuickSight  
- **AWS Services**: S3, Glue, Athena, QuickSight, Lambda  



### [📷 Image Recognition Pipeline](https://github.com/Salma22C/awsprojects/tree/main/Serverless%20Image%20Recognition%20Pipeline)  
Automatically tags images uploaded to an S3 bucket using a serverless Rekognition pipeline.  
- **AWS Services**: Lambda, S3, Rekognition, CloudWatch  


### [🛡️ High Availability & Security for PHP Apps](https://github.com/Salma22C/awsprojects/tree/main/High%20Availability%20PHP%20App)  
Deployed a PHP web app with high availability and resilience.  
- **Features**:
  - Multi-AZ RDS backend  
  - Load-balanced EC2 instances  
  - Auto Scaling with health checks  
- **AWS Services**: EC2, ALB, Auto Scaling Group, RDS, Security Groups  




## 🧰 Tools & Technologies

<p align="left">
  <img src="https://img.shields.io/badge/AWS-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white" alt="AWS"/>
  <img src="https://img.shields.io/badge/Lambda-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white" alt="AWS Lambda"/>
  <img src="https://img.shields.io/badge/DynamoDB-4053D6?style=for-the-badge&logo=amazonaws&logoColor=white" alt="Amazon DynamoDB"/>
  <img src="https://img.shields.io/badge/S3-569A31?style=for-the-badge&logo=amazonaws&logoColor=white" alt="Amazon S3"/>
  <img src="https://img.shields.io/badge/EventBridge-FF4F8B?style=for-the-badge&logo=amazonaws&logoColor=white" alt="Amazon EventBridge"/>
  <img src="https://img.shields.io/badge/CloudWatch-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white" alt="Amazon CloudWatch"/>
  <img src="https://img.shields.io/badge/VPC-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white" alt="Amazon VPC"/>
  <img src="https://img.shields.io/badge/Polly-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white" alt="Amazon Polly"/>
  <img src="https://img.shields.io/badge/Comprehend-4CAF50?style=for-the-badge&logo=amazonaws&logoColor=white" alt="Amazon Comprehend"/>
  <img src="https://img.shields.io/badge/Rekognition-3EB489?style=for-the-badge&logo=amazonaws&logoColor=white" alt="Amazon Rekognition"/>
  <img src="https://img.shields.io/badge/QuickSight-0052CC?style=for-the-badge&logo=amazonaws&logoColor=white" alt="Amazon QuickSight"/>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python"/>
  <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" alt="Linux"/>
  <img src="https://img.shields.io/badge/Terraform-7B42BC?style=for-the-badge&logo=terraform&logoColor=white" alt="Terraform"/>
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git"/>
  <img src="https://img.shields.io/badge/PowerBI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black" alt="Power BI"/>
</p>




## 🧑‍🏫 Training Experience
Alongside building cloud-native solutions, I’ve also served as a Cloud & DevOps Trainer at ICT Hub, Cairo, where I delivered hands-on AWS training to early-career engineers and students.

My training focused on:

```
    - Learning by building — guiding students through real-world projects like serverless text-to-speech apps, cost dashboards, and AI-powered automation.
    - Real-world application — using AWS Free Tier to simulate production environments with services like Lambda, S3, Athena, Rekognition, and Bedrock.
    - Feedback-driven teaching — creating a collaborative, supportive environment that helped learners build confidence alongside technical skills.
```
    
    💬 “Before this course, cloud computing felt overwhelming. But these hands-on projects made everything click. I now feel ready to build and present my own cloud solutions.”
    — Student, AWS Training Program

## 🔗 Explore More

👩‍💻 **GitHub Portfolio:**  
👉 [github.com/Salma22C/awsprojects](https://github.com/Salma22C/awsprojects)

📫 **Connect with Me:**  
- 💼 [LinkedIn – Salma Mohamed Kassem](https://www.linkedin.com/in/salma-mohamed-kassem)  
- 📧 [Email – salmakassem6@gmail.com](mailto:salmakassem6@gmail.com)




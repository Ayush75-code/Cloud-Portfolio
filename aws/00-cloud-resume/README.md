# AWS Project 0: Cloud Resume Challenge

> Serverless resume website with visitor counter

## 🎯 Overview

A static resume website hosted on AWS with a serverless backend for tracking visitors.

## 🏗️ Architecture

```
┌─────────────────┐     ┌─────────────────┐     ┌─────────────────┐
│   CloudFront    │────▶│       S3        │     │    Route 53     │
│   (CDN + HTTPS) │     │ (Static Website)│     │   (DNS + SSL)   │
└─────────────────┘     └─────────────────┘     └─────────────────┘
         │
         ▼
┌─────────────────┐     ┌─────────────────┐
│   API Gateway   │────▶│     Lambda      │
│   (REST API)    │     │ (Visitor Count) │
└─────────────────┘     └─────────────────┘
                               │
                               ▼
                        ┌─────────────────┐
                        │    DynamoDB     │
                        │  (Counter DB)   │
                        └─────────────────┘
```

## 🛠️ Technologies Used

- **Frontend:** HTML, CSS, JavaScript
- **Hosting:** S3, CloudFront
- **Backend:** Lambda (Python), API Gateway
- **Database:** DynamoDB
- **IaC:** Terraform
- **CI/CD:** GitHub Actions

## 📊 Key Features

- [ ] Static website with responsive design
- [ ] HTTPS with custom domain
- [ ] Visitor counter with real-time updates
- [ ] Infrastructure as Code (Terraform)
- [ ] Automated deployments

## 📈 Results

*To be updated after completion*

- Latency: < 100ms globally
- Cost: < $2/month
- Uptime: 99.9%

## 📚 What I Learned

*To be documented during project*

---

*Status: 🔲 Not Started*

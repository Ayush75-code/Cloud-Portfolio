# GCP Project G1: Cloud Resume Challenge (GCP Version)

> Serverless resume website on Google Cloud Platform

## 🎯 Overview

GCP version of the Cloud Resume Challenge, demonstrating multi-cloud skills.

## 🏗️ Architecture

```
┌─────────────────┐     ┌─────────────────┐     ┌─────────────────┐
│    Cloud CDN    │────▶│  Cloud Storage  │     │    Cloud DNS    │
│   (Edge Cache)  │     │ (Static Website)│     │   (Domain)      │
└─────────────────┘     └─────────────────┘     └─────────────────┘
         │
         ▼
┌─────────────────┐     ┌─────────────────┐
│  Cloud Functions│     │    Firestore    │
│ (Visitor Count) │────▶│  (Counter DB)   │
└─────────────────┘     └─────────────────┘
```

## 🛠️ Technologies Used

- **Frontend:** HTML, CSS, JavaScript
- **Hosting:** Cloud Storage, Cloud CDN
- **Backend:** Cloud Functions (Python)
- **Database:** Firestore
- **IaC:** Terraform (GCP Provider)
- **CI/CD:** Cloud Build

## 📊 Key Features

- [ ] Static website hosting
- [ ] Global CDN distribution
- [ ] Serverless visitor counter
- [ ] Terraform infrastructure
- [ ] Automated deployments

## 📈 Results

*To be updated after completion*

---

*Status: 🔲 Not Started*

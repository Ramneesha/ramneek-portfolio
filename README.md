# 🌐 Personal Portfolio Website

## 📌 Overview

This project is my personal portfolio website designed to showcase my skills, projects, and experience in cloud computing and web development. It is fully responsive and deployed on AWS using scalable and secure architecture.

---

## 🚀 Live Demo

🔗 http://ramneek-portfolio.s3-website.ap-south-1.amazonaws.com/

---

## 🏗️ Architecture

User → CloudFront (CDN + HTTPS) → S3 Bucket (Static Website Hosting)

---

## 🛠️ Tech Stack

* HTML
* CSS
* JavaScript
* AWS S3 (Static Hosting)
* AWS CloudFront (CDN + HTTPS)

---

## ✨ Features

* Responsive design (mobile-friendly)
* Clean and modern UI
* Smooth scrolling and animations
* Fast content delivery using CDN
* Secure access via HTTPS

---

## ⚙️ Deployment Steps

### 1. Upload Website to S3

* Created an S3 bucket
* Enabled static website hosting
* Uploaded project files

### 2. Configure Permissions

* Enabled public access for static hosting
* Added bucket policy

### 3. Setup CloudFront

* Created CloudFront distribution
* Connected S3 bucket as origin
* Enabled HTTPS

---

## 📸 Screenshots

### 🔹 Live Website
![Live Website](screenshots/website-live.png)

### 🔹 Bucket Policy
![Bucket Policy](screenshots/bucket-policy.png)

### 🔹 S3 Endpoint Link
![S3 Link](screenshots/s3hostinglink.png)

```

---

## 📂 Project Structure

```id="c1t9qn"
├── index.html
├── style.css
├── script.js
├── screenshots/
```

---

## 📌 Key Learnings

* Hosting static websites on AWS S3
* Using CloudFront for CDN and performance optimization
* Managing permissions and bucket policies
* Improving website performance and security

---

## 🚀 Future Improvements

* Add custom domain (Route 53)
* Implement CI/CD using GitHub Actions
* Improve UI with advanced animations
* Add backend integration (contact form with AWS Lambda)

---

## 📄 License

This project is licensed under the MIT License.

# s3_website_hosting
Deployed a static website using Amazon Web Services and hosted it on Amazon S3, enabling static website hosting with proper bucket configuration and public access policies.
📌 Static Website Deployment Using Amazon S3
📖 Project Overview

This project demonstrates how to deploy a static website using Amazon Web Services and host it using Amazon S3.

The website contains:

HTML
CSS
JavaScript
Images
Videos

No backend server or database is used.
 Objectives
Understand static website architecture
Learn how Amazon S3 can act as a web server
Configure bucket policies for public access
Understand HTTP request-response lifecycle

🛠 Tech Stack
Frontend:
HTML
CSS
JavaScript
Cloud:
AWS
Amazon S3

📂 Project Structure
static-website/
│
├── index.html
├── css/style.css
├── js/script.js
├── images/banner.jpg
├── videos/intro.mp4

⚙️ Deployment Steps
Created an S3 bucket (globally unique name)
Uploaded all website files
Enabled Static Website Hosting
Set index document as index.html
Configured bucket policy to allow public read access

🌐 How It Works
When a user enters the website URL:
Browser sends HTTP request
Request reaches S3 endpoint
S3 returns index.html
Browser loads CSS, JS, images, and videos
Website renders completely
Amazon S3 acts as a read-only web server that serves static files.

🚀 Features
Fully responsive static website
Cloud-hosted
Publicly accessible
Simple and cost-effective deployment




Implement HTTPS

Add CI/CD pipeline

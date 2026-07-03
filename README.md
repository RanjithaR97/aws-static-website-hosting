# aws-static-website-hosting
Deploying a static website on AWS using Amazon S3, CloudFront, CloudWatch, and SNS with monitoring and notifications.

# AWS Static Website Hosting using Amazon S3, CloudFront, CloudWatch & SNS

## Project Overview

This project demonstrates how to host a static website on AWS using Amazon S3, accelerate content delivery with Amazon CloudFront, monitor performance using Amazon CloudWatch, and configure Amazon SNS for notifications. The solution provides a scalable, secure, and highly available static website hosting architecture.

---

## Objective

Deploy a static website on AWS and implement content delivery, monitoring, and notification services using core AWS offerings.

---

## AWS Services Used

* Amazon S3
* Amazon CloudFront
* Amazon CloudWatch
* Amazon SNS

---

## Features

* Static website hosting using Amazon S3
* Global content delivery with CloudFront
* Performance monitoring through CloudWatch
* Alert notifications using Amazon SNS
* Secure and scalable cloud architecture

---

## Prerequisites

* AWS Account
* IAM User with appropriate permissions
* Static website files (HTML, CSS, JavaScript)
* Internet connection
* Basic knowledge of AWS Console

---

## Project Architecture

User Request

↓

Amazon CloudFront

↓

Amazon S3 Static Website

↓

Amazon CloudWatch

↓

Amazon SNS Notifications

---

## Implementation Steps

### Step 1: Create an Amazon S3 Bucket

* Created a new S3 bucket.
* Configured bucket settings.
* Uploaded HTML, CSS, JavaScript, and image files.

### Step 2: Enable Static Website Hosting

* Enabled Static Website Hosting.
* Configured the index document.
* Generated the website endpoint URL.

### Step 3: Configure Amazon CloudFront

* Created a CloudFront distribution.
* Selected the S3 bucket as the origin.
* Waited for deployment.
* Verified website access through the CloudFront domain.

### Step 4: Monitor Using Amazon CloudWatch

* Viewed request metrics.
* Monitored traffic and performance.
* Configured monitoring dashboards.

### Step 5: Configure Amazon SNS

* Created an SNS topic.
* Added an email subscription.
* Confirmed the subscription.
* Configured notifications for important events.

---

## Testing

* Verified the website using the S3 website endpoint.
* Verified website access using the CloudFront URL.
* Checked CloudWatch metrics.
* Confirmed SNS notification delivery.

---

## Project Outcome

Successfully deployed a static website on AWS using Amazon S3 and CloudFront. Implemented monitoring using Amazon CloudWatch and configured Amazon SNS notifications, resulting in a secure, scalable, and monitored cloud-hosted website.

---

## Folder Structure

```text
aws-static-website-hosting/
│
├── README.md
├── website/
│   ├── index.html
│   ├── style.css
│   ├── script.js
│
├── screenshots/
│   ├── 01-s3-bucket.png
│   ├── 02-static-hosting.png
│   ├── 03-cloudfront.png
│   ├── 04-cloudwatch.png
│   ├── 05-sns.png
│   └── 06-final-output.png
│


---

## Screenshots

output of all are added in folder screenshots


---

## Skills Demonstrated

* Amazon S3
* Amazon CloudFront
* Amazon CloudWatch
* Amazon SNS
* Static Website Hosting
* Cloud Monitoring
* AWS Networking Basics
* AWS Console Management

---

## Learning Outcomes

* Learned how to host a static website using Amazon S3.
* Understood CloudFront content delivery and caching.
* Gained experience monitoring AWS resources using CloudWatch.
* Configured SNS for automated notifications.
* Built an end-to-end AWS static website hosting solution.

---






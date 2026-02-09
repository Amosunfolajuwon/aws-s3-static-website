# AWS S3 Static Website Project

## Overview
This project demonstrates hosting a static HTML page on **AWS S3** and delivering it via **CloudFront** for HTTPS and faster performance. The website is a simple "Hello, AWS!" page.

## Live URL
[View Live Website](https://d1234abcd.cloudfront.net)

*(Replace the URL above with your actual CloudFront domain if it’s different.)*

## Project Structure
aws-s3-static-website/
│
├─ index.html # Main HTML page
├─ README.md # Project description
└─ screenshots/ # Screenshots of AWS setup

## Services Used
- **Amazon S3** → Static website hosting
- **CloudFront** → CDN + HTTPS
- **GitHub** → Project repository for backup and portfolio

## Steps Taken
1. Created an S3 bucket and uploaded `index.html`.
2. Enabled static website hosting on the bucket.
3. Configured bucket policy for public read access.
4. Created CloudFront distribution using the S3 website endpoint.
5. Verified the live website in the browser.
6. Uploaded project files and screenshots to GitHub.

## Key Learnings
- Hosting static websites with S3.
- Setting up CloudFront for HTTPS.
- Managing AWS bucket permissions.
- Using GitHub for version control and portfolio showcase.

# AWS S3 Static Website Hosting

## Overview
Deployed a static website using Amazon S3 static 
website hosting. Configured bucket permissions, 
uploaded web files, and resolved access control 
issues to make the site publicly accessible.

## What I Built
- S3 bucket created in us-east-1 (N. Virginia)
- Static website hosting enabled with index.html
- Uploaded HTML files to the bucket
- Configured public access settings
- Resolved 403 Forbidden access error

## Steps

### 1. Created S3 Bucket
Created a new S3 bucket named "nanomoo.click" 
in the US East region.

![Bucket Created](AWS%S3%screenshots/Bucket%created.png)

### 2. Uploaded Website Files
Uploaded index.html to the bucket as the 
main entry point for the website.

![Objects Added](AWS%S3%screenshots/Objects%added.png)

### 3. Enabled Static Website Hosting
Configured the bucket to host a static website 
with index.html as the index document.

![Static Website Hosting](AWS%S3%screenshots/Static%website%hosting%enabled.png)

### 4. Troubleshot 403 Forbidden Error
Encountered and resolved a 403 Access Denied 
error by configuring the correct bucket policy 
to allow public read access.

![403 Error](AWS%S3%screenshots/403%Forbidden%Error.png)

### 5. Website Live
Successfully deployed the website and confirmed 
it was publicly accessible.

![Website Live](AWS%S3%screenshots/Website%live.png)

## Key Concepts Demonstrated
- S3 bucket creation and configuration
- Static website hosting setup
- Bucket policy and public access settings
- Troubleshooting AWS permission errors

## Services Used
- Amazon S3
- S3 Static Website Hosting﻿
# AWS S3 Static Website Hosting

This project demonstrates how to host a static website using Amazon S3.

##  Project Overview
I used AWS S3’s **Static Website Hosting** feature to deploy a simple static site. The setup involved:

-Enabling static website hosting on an S3 bucket
Uploading "index.html" 

The site was accessible through the S3 generated website endpoint. After completing the project and documentation, the bucket was deleted.

##  Documentation
Detailed configuration steps and explanation are available in:

 [`S3 static website hosting project.pdf`](S3%20static%20website%20hosting%20project.pdf)

##  Files Included
index.html – Main webpage

S3 static website hosting project.pdf – Full setup guide and explanation

##  Technologies Used
Amazon S3 (Static Website Hosting)

---

This project is part of my [AWS Cloud Projects Portfolio](../README.md).

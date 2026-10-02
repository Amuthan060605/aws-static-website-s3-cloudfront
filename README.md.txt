# Static Website Hosting on AWS

## Project Overview

A static website hosted on Amazon S3 and distributed globally using Amazon CloudFront.

## AWS Services Used

- Amazon S3
- Amazon CloudFront
- Origin Access Control (OAC)
- S3 Bucket Policy
- HTTPS

## Architecture

User
↓
CloudFront
↓
Origin Access Control
↓
Private S3 Bucket

## Features

- Static website hosting
- Global content delivery using CloudFront
- HTTPS
- Private S3 bucket
- Origin Access Control
- S3 bucket policy
- CloudFront caching
- Cache invalidation

## Implementation

1. Created an Amazon S3 bucket.
2. Uploaded HTML and CSS files.
3. Enabled S3 Block Public Access.
4. Created a CloudFront distribution.
5. Configured S3 as the CloudFront origin.
6. Configured Origin Access Control.
7. Allowed CloudFront to access S3 using an S3 bucket policy.
8. Configured HTTPS.
9. Tested the website through the CloudFront domain.
10. Tested direct S3 access and received Access Denied.
11. Tested CloudFront cache invalidation.

## Security

The S3 bucket is private. Direct access to S3 objects is blocked, while CloudFront is authorized to retrieve the objects through Origin Access Control.

## Live Website

https://d2dz27uve7jx2b.cloudfront.net/

## Technologies

HTML  
CSS  
Amazon S3  
Amazon CloudFront  
AWS OAC
# Dynamic-Content-Website-with-AWS-Integration
Project Title: Dynamic Content Website with AWS Integration
Objective
Create a web application hosted on an EC2 instance, using PHP to handle dynamic content and AWS SDK to interact with S3 for media storage, RDS for database management, and CloudFront for content delivery.

Architecture Overview
EC2 Instance: Web server setup with LAMP stack (Linux, Apache, MySQL, PHP).
EBS: Storage for EC2 instance for scalable and persistent storage of your application files.
S3: Store and retrieve images, videos, or static assets of the website.
RDS: Use MySQL/PostgreSQL database for storing user data, comments, or dynamic website data.
CloudFront: Distribute the static content globally with low latency.
AWS SDK (PHP): Enable programmatic access to S3 or other services from your PHP application

# Project Report
## Student Portfolio Website Using Amazon S3 and AWS CloudFormation

### 1. Abstract
This project contains a static student portfolio website and a CloudFormation template describing the AWS infrastructure required to host it on Amazon S3. It introduces cloud storage and Infrastructure as Code concepts.

### 2. Introduction
Cloud computing provides access to computing resources over the internet. AWS provides services for storage, computing, networking, and infrastructure management. Amazon S3 can host static website files without managing a traditional web server.

### 3. Problem statement
A student needs a simple portfolio website and a beginner-friendly example of how cloud infrastructure can be described in code.

### 4. Objectives
1. Create a responsive portfolio website using HTML and CSS.
2. Understand Amazon S3 buckets and static website hosting.
3. Understand AWS CloudFormation and Infrastructure as Code.
4. Prepare a YAML template for an S3 website bucket.
5. Document architecture, testing, and deployment steps.

### 5. Tools and technologies
HTML5, CSS3, Amazon S3, AWS CloudFormation, YAML, and a web browser.

### 6. Methodology
1. Create the page structure using HTML.
2. Style the website using CSS.
3. Write a CloudFormation template defining an S3 bucket.
4. Configure the bucket for static website hosting.
5. Add a bucket policy allowing public read access to website objects.
6. Open the website locally and inspect the template.
7. If deployment is required, create the stack in an AWS account, upload the website files, and test the endpoint.

### 7. Expected result
The website opens locally in a browser. After actual AWS deployment and upload, the S3 website endpoint can serve the portfolio page.

### 8. Advantages
- Beginner-friendly cloud project.
- Demonstrates object storage and Infrastructure as Code.
- No virtual machine administration is required.
- Infrastructure is described in a reusable YAML template.

### 9. Limitations and security
This is a static website without a database, login, or server-side processing. The supplied template has not been deployed. It permits public reads of website objects, so only non-sensitive content should be used. S3 website endpoints do not directly provide HTTPS; production deployments should use an appropriate HTTPS architecture such as CloudFront.

### 10. Conclusion
The project demonstrates how a static website can be prepared for Amazon S3 and how AWS CloudFormation can describe the required infrastructure.

### Submission status
Source code, CloudFormation template, and documentation are included. 
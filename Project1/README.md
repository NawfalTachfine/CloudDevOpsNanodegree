# Project 1: Deploying a Static Website to AWS

## Website Files

1. Created *S3* bucket `udacity-devops-static-website` to host website files.
![step1-1](assets/markdown-img-paste-20201004170542370.png)

2. Uploaded website files to the bucket.
![step1-2](assets/markdown-img-paste-20201004170635846.png)

3. Added *IAM* policy to make bucket content publicly accessible.
![step1-3](assets/markdown-img-paste-20201004170829588.png)

4. Configured bucket to support static website hosting.
![step1-4](assets/markdown-img-paste-2020100417100517.png)

## Website Distribution
Configured *CloudFront* to retrieve and distribute website files.
![step2-1](assets/markdown-img-paste-20201004171851852.png)
![step2-2](assets/markdown-img-paste-20201004171938801.png)

## Web Browser Access
Made website accessible to anyone through a [*CloudFront* endpoint](https://d1kyal3w1pddva.cloudfront.net/index.html).
![step3](assets/markdown-img-paste-20201004172039819.png)

## Bonus
Customized website name and header image.

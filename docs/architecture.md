# System Architecture

```text
Website visitor's browser
          |
          | HTTP request (after deployment)
          v
Amazon S3 website endpoint
          |
          v
S3 bucket: index.html + style.css

Infrastructure definition:
aws/template.yaml
          |
          v
AWS CloudFormation
          |
          v
Creates S3 bucket, website configuration,
and bucket policy
```

HTML defines page content. CSS controls presentation. Amazon S3 stores the website objects. AWS CloudFormation describes the infrastructure as code. This is the intended architecture after deployment, not proof that deployment has occurred.

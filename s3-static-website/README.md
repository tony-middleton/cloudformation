# s3-static-website

###A CloudFormation script that creates a static website on S3.

## Features

- Creates S3 bucket
- Sets up `index.html` and `error.html` as the main bucket's index and errors documents
- Grants read access to everyone in the world to the S3 bucket


## Usage

1. Login to your **AWS console**
1. Go to CloudFormation, click **create stack**
1. In Select Template, choose **Upload a template to Amazon S3** and choose the s3-static-website.yaml and click Next
1. In **Stack name** enter a sensible name (it doesn't matter), in **BucketName** enter the bucket name and click Next
1. Click Next again and click Create

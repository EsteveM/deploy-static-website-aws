# Deploy a Static Website on AWS

This project is intended to deploy a static website on the cloud, in particular, on AWS.

## Table of Contents

* [Description of the Project](#description-of-the-project)
* [Getting Started](#getting-started)
* [Contributing](#contributing)

## Description of the Project

As has already been mentioned, this project deploys a static website on AWS. The work that has been done is best described by explaining its main steps:

* An S3 bucket is created.
* The website files are uploaded to the bucket.
* The bucket is configured for website hosting.
* The bucket is secured using IAM policies.
* The website is distributed using CloudFront.
* The website is accessed in a browser using the CloudFront endpoint.

## Getting Started

These are the steps followed to accomplish the project goal:

* Firstly, the S3 bucket is created.
![1S3bucketcreationv11](/ScreenShots11/1S3bucketcreationv11.png)
* Secondly, the website files are uploaded to the S3 bucket.
![2FilesuploadedtoS3bucket11](/ScreenShots11/2FilesuploadedtoS3bucket11.png)
* Thirdly, the bucket is configured for website hosting.
![3S3bucketconfigurationwebsitehosting11](/ScreenShots11/3S3bucketconfigurationwebsitehosting11.png)
* In the fourth place, the bucket is secured using IAM policies.
![4IAMbucketpolicy11](/ScreenShots11/4IAMbucketpolicy11.png)
* In the fifth place, the website is distributed using CloudFront.
![5CloudFrontdistribution11](/ScreenShots11/5CloudFrontdistribution11.png)
* Finally, the website is accessed in a browser using the CloudFront endpoint.
![6AccessWebsiteinWebBrowser11](/ScreenShots11/6AccessWebsiteinWebBrowser11.png)

## Contributing

This repository contains all the work that makes up the project. Individuals and I myself are encouraged to further improve this project. As a result, I will be more than happy to consider any pull requests.

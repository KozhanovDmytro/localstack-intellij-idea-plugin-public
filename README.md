# LocalStack Plugin for IntelliJ IDEA 🚀
## Table of Contents
1. [Description](#description)
2. [Configuration](#configuration)
3. [Services](#services)
    - [SQS](#sqs)
    - [S3](#s3)
    - [SNS](#sns)
    - [Lambda](#lambda)
4. [Troubleshooting](#troubleshooting)
5. [Donations](#donations)

## Description
The LocalStack plugin for IntelliJ IDEA is designed exclusively for IntelliJ IDEA users, enabling them to create and 
manage resources in LocalStack directly from their IDE. This plugin supports several AWS services like SQS, S3, SNS, 
and Lambda, with ongoing development to introduce more services in the future. 

Given our small development team, we are unable to add a large number of services quickly. If you find this project 
helpful, please consider supporting us by purchasing a subscription or making a donation. The plugin operates on a 
freemium model, offering both free and paid features.

![test](./images/plugin_general.png)

## Configuration
To integrate LocalStack into your IntelliJ IDEA environment seamlessly, the plugin allows for easy configuration 
of various LocalStack settings, including:
- URL
- Region
- Access Key and Secret Keys
- Timeout settings

These configurations ensure that your LocalStack environment aligns with your project's needs.

In order to configure these settings please follow the steps:
1. Go to `File` -> `Settings`
2. On the left side, select Tools and then choose `LocalStack Plugin Settings`.
3. Apply your changes, and
4. Restart you IDE and enjoy :)

![test](./images/configuration.png)

## Services
The plugin provides support for a range of services, each with its own set of features:

### SQS
- Create SQS queue (Standard) 🆓
- Create SQS queue (FIFO) 🔒
- Create SQS queue (Advanced) 🔒
- Get list of queues 🆓
- View queue attributes 🆓
- Send message to queue 🆓
- Receive a message from queue 🆓
- Receive a message from queue (Recording mode) 🔒
- Beautify received message (JSON) 🔒
- Copy received message 🔒
- Purge queue 🆓
- Delete queue 🆓

### S3
- Create S3 bucket (Simple) 🆓
- Get list of S3 buckets 🆓
- Delete S3 bucket 🆓
- Create folders in S3 bucket
- Navigate through S3 bucket folders
- Upload objects to S3 buckets
- Upload folders to S3 buckets
- Upload objects to S3 buckets from Project View pop-up 🔒
- Upload folders to S3 buckets from Project View pop-up 🔒
- Delete objects from S3 bucket
- View objects in S3 bucket

### SNS
- Create SNS topic (Simple)
- View SNS topic attributes
- Delete SNS topic

### Lambda
- Create Lambda function
- Invoke Lambda function
- Delete Lambda function

## Troubleshooting
Encountering issues? Our troubleshooting guide can help you resolve common problems and errors. For additional support, feel free to reach out through our community forums or support channels.

_Image Placeholder for Troubleshooting Tips_

## Donations
Love the LocalStack plugin for IntelliJ IDEA? Consider supporting our project through donations or by purchasing a subscription. Your support helps us maintain and expand the plugin's capabilities, ensuring it meets the community's needs.

1. [PayPal](https://www.paypal.com/donate/?hosted_button_id=Y3KMBWW4WVESS)
2. [BuyMeACoffee](https://www.buymeacoffee.com/dmytro.kozhanov)
3. or just [purchase a subscription](https://plugins.jetbrains.com/plugin/22223-localstack-integrator/pricing#tabs).

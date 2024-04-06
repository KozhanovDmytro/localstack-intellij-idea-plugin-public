# LocalStack Plugin for IntelliJ IDEA
## Description

The LocalStack plugin for IntelliJ IDEA is designed to streamline the development and testing of AWS services locally. With this plugin, users can effortlessly create and manage resources in LocalStack, an open-source, fully functional local AWS cloud stack.
Currently, the plugin supports a range of services including:
- SQS,
- S3,
- SNS, and
- Lambda

Given the limited size of our development team, the pace at which new services can be introduced is constrained. Therefore, the plugin adopts a freemium model, offering a core set of functionalities for free, with advanced features available through a subscription. Users who find value in this project and wish to support its development can consider purchasing a subscription or making a donation on our donation page.

![Place Image Placeholder]

## Configuration

To use the LocalStack plugin effectively, users must configure it with their LocalStack instance. The configuration includes:

- **URL**: The endpoint URL for the LocalStack services.
- **Region**: The AWS region to mimic.
- **Access Key and Secret Keys**: Credentials for accessing LocalStack services.
- **Timeout**: Customizable timeout settings for operations.

![Configuration Image Placeholder]

## Services

The plugin encompasses a variety of services, detailed below, with both free and paid features.

### 3.1. SQS

- **Create SQS queue (Standard)** (Free)
- **Create SQS queue (FIFO)** (Paid feature)
- **Create SQS queue (Advanced)** (Paid)
- **Get list of queues** (Free)
- **View queue attributes** (Free)
- **Send message to queue** (Free)
- **Receive a message from queue** (Free)
- **Receive a message from queue (Recording mode)** (Paid)
- **Beautify received message (JSON)** (Paid)
- **Copy received message** (Paid)
- **Purge queue** (Free)
- **Delete queue** (Free)

### 3.2. S3

- **Create S3 bucket (Simple)** (Free)
- **Get list of S3 buckets** (Free)
- **Delete S3 bucket** (Free)
- **Create folders in S3 bucket**
- **Navigate through S3 bucket folders**
- **Upload objects to S3 buckets**
- **Upload folders to S3 buckets**
- **Upload objects to S3 buckets from Project View pop-up** (Paid)
- **Upload folders to S3 buckets from Project View pop-up** (Paid)
- **Delete objects from S3 bucket**
- **View objects in S3 bucket**

### 3.3. SNS

- **Create SNS topic (Simple)**
- **View SNS topic attributes**
- **Delete SNS topic**

### 3.4. Lambda

- **Create Lambda function**
- **Invoke Lambda function**
- **Delete Lambda function**

## Troubleshooting

This section is intended to address common issues users may encounter while using the LocalStack plugin for IntelliJ IDEA. It will include solutions to frequent setup and operational problems.

![Troubleshooting Image Placeholder]

## Donations

Supporting the LocalStack plugin for IntelliJ IDEA helps us to continually improve and expand the plugin's capabilities. If you find the plugin valuable and would like to contribute to its development, please visit our donation page. Your support is greatly appreciated and plays a crucial role in the ongoing development of this project.

![Donations Image Placeholder]

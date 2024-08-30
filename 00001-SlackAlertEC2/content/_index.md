# Monitor CPU and memory of EC2 with AWS Lambda, CloudWatch, Slack

### Overview

This article demonstrates how to monitor EC2 instances for high CPU utilization or full disk usage and send alerts to a Slack channel using AWS CloudWatch and AWS Lambda.

The deployment model is illustrated below:

### Content

1. [Prepare](1-prerequisite)
2. [Setup slack webhook](2-setup-slack-webhook)
3. [Create IAM Role](3-create-iam-role)
4. [Setup python library](4-add-python-library)
5. [Create CloudWatch](6-create-cloud-watch)
6. [Create lambda function](5-create-lambda-function)
7. [Check result](6-check-result)

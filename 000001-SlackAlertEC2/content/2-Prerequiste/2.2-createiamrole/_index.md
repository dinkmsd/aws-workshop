---
title: "Create IAM Role"
date: "`r Sys.Date()`"
weight: 2
chapter: false
pre: " <b> 2.2 </b> "
---

### Create IAM Role

In this step, we will proceed to create IAM Role. In this IAM Role, the policy **AWSLambdaBasicExecutionRole** and **CloudWatchReadOnlyAccess** will be assigned, this is the policy that allows the Lambda to communicate with the CloudWatch.

1. Go to [IAM service administration interface](https://console.aws.amazon.com/iamv2/)
2. In the left navigation bar, click **Roles**.

![role](/images/2.prerequisite/038-iamrole.png)

3. Click **Create role**.

![role1](/images/2.prerequisite/039-iamrole.png)

4. In the Search box, enter **AWSLambdaBasicExecutionRole** and **CloudWatchReadOnlyAccess** then press Enter to search for this policy.

- Click the policy **AmazonSSMManagedInstanceCore**.
- Click **Next: Tags.**

![createpolicy](/images/2.prerequisite/001-iam-roles.png)

5. Click **Next: Review**.
6. Name the Role **LambdaCloudWatchSlackRole** in Role Name

- Click **Create Role** \.

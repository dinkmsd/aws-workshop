---
title: "Create Cloud Watch Service"
date: "`r Sys.Date()`"
weight: 3
chapter: false
pre: " <b> 3. </b> "
---

In this step, we will create CloudWatch service to Monitor EC2 CPU.

1. Select Service CloudWatch
   ![alt text](/images/3.cloud-watch/001.cloud-watch-service.png)
2. Create Alarm
   ![alt text](/images/3.cloud-watch/002.create-alarm.png)
3. Choose metric is EC2 was created and metric named `CPUUtilization`
   ![alt text](/images/3.cloud-watch/003.png)
   ![alt text](/images/3.cloud-watch/004.png)
4. Setup param
   ![alt text](/images/3.cloud-watch/005.png)
5. Add lambda function
   ![alt text](/images/3.cloud-watch/006.png)

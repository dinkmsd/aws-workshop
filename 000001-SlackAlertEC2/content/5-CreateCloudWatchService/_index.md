---
title: "Create CloudWatch Service"
date: "`r Sys.Date()`"
weight: 5
chapter: false
pre: " <b> 5. </b> "
---

In this step, we will create CloudWatch service to Monitor EC2 CPU.

1. Select Service CloudWatch
   ![alt text](/images/3.cloud-watch/001.cloud-watch-service.png)
2. Create Alarm
   ![alt text](image-8.png)
3. Choose metric is EC2 was created and metric named `CPUUtilization`
   ![alt text](image-1.png)  
   ![alt text](image.png)
4. Setup param
   ![alt text](image-2.png)
5. Add lambda function
   ![alt text](image-3.png)
6. Enter name and create alarm
   ![alt text](image-4.png)
7. Assign lambda trigger permission for alarm
   ![alt text](image-6.png)
8. Fill bellow infomation
   ![alt text](image-7.png)

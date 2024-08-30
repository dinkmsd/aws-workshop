## Create an IAM Role for Lambda

1. Create an IAM Role:

- Go to the AWS Management Console and open the IAM service.
  ![alt text](<Screenshot 2024-08-25 090657.png>)
- Click on "Roles" in the sidebar and then "Create role."
  ![alt text](<Screenshot 2024-08-25 090816.png>)
- Select "AWS service" and choose "Lambda" as the use case.
  ![alt text](<Screenshot 2024-08-25 090854.png>)
- Attach the following policies:
  - `AWSLambdaBasicExecutionRole` (allows Lambda to write logs to CloudWatch)
  - `CloudWatchReadOnlyAccess` (allows Lambda to read CloudWatch metrics)
    ![alt text](<Screenshot 2024-08-25 091144.png>)
- Name the role `LambdaCloudWatchSlackRole` and create the role.

## Setting Up Slack Webhook

1. Create a New Slack App:

- Access **https://api.slack.com/apps** to create Slack App
  ![alt text](<Screenshot 2024-08-25 090435.png>)
- Click "Create New App" and select "From scratch."
- Name your app (e.g., `AWS Alerts`) and choose a workspace to install it.

2. Enable Incoming Webhooks:

- In the Slack app settings, navigate to "Incoming Webhooks."
- Click "Activate Incoming Webhooks."
  ![alt text](<Screenshot 2024-08-25 090543.png>)
- Click "Add New Webhook to Workspace" and select a channel to post alerts (e.g., `#alerts`).
- Save the generated Webhook URL; you will need it later.

# Game Day Notification Serverless App Using AWS Services 🎮

![Game Day Notification](https://github.com/Preshydee/game_day_notification_project/blob/main/Game%20Day%20App%20Architecture.drawio.png)

## Overview
This project is a serverless notification system built using AWS Lambda, SNS, and EventBridge to send fans or subscribers real-time NBA game schedule updates.

## How It Works
- **Fetch Game Data**: An AWS Lambda function retrieves NBA schedules from an external API.
- **Send Notifications**: Processed data is sent to AWS SNS to notify subscribers via email/SMS.
- **Automate with EventBridge**: AWS EventBridge triggers the Lambda function daily at 1 PM.

## Technologies Used
- **AWS Lambda** (Serverless function execution)
- **AWS SNS** (Notification delivery)
- **AWS EventBridge** (Automated scheduling)
- **Python** (Data processing & API handling)
- **CloudWatch** (Monitoring & logging)

## Setup Instructions
1. Create an SNS Topic and subscribe via email/SMS.
2. Deploy the Lambda Function using the provided code.
3. Set up an EventBridge Rule to trigger the function daily.

## Live Demo
Subscribe to receive game alerts and never miss a match!

🔗 **GitHub Repository**: [Game Day Notification Project](https://github.com/Preshydee/game_day_notification_project)




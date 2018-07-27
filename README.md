# auto-publish-email
## Trigger
This application will be triggered by a message on RabbitMQ.
## Process
The application will:
- Get all organisations
- For every organisation
    - Get statistics about their archive
    - Get users from this organisation
    - For every user
        - Use glue (Campaign Monitor) to send an email to the user
- Send a notification to Slack with the emails sent per organisation
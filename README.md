# Simple-Queue-Service-AWS

Amazon Simple Queue Service (SQS) is a fully managed message queuing service that enables you to decouple and scale microservices, distributed systems, and serverless applications.

Steps to send a Notification through Lambda When a Message is Sent to SQS-

```

    1. Create a Queue
    2. Create an SNS topic
    3. Create an email subscription for it.
    4. Create a Lambda function to publish a message to the SNS topic
    5. Create an email subscription for it.
    6. Test the application
    
 ```

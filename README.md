# Simple-Queue-Service-AWS

Amazon Simple Queue Service (SQS) is a fully managed message queuing service that enables you to decouple and scale microservices, distributed systems, and serverless applications.

Steps to demonstrate SNS-

```
Part 1
    1. Create a Queue
    2. Create an SNS topic
    3. Create an email subscription for it.
    4. Create a Lambda function to publish a message to the SNS topic
    5. Create an email subscription for it.
    6. Test the application
    
Part 2
    1. Go to the AWS Management Console, select AWS Services, and under the Application Integration, click on Simple Notification Service.
    2. To create a topic, click on Create Topic.
    3. Enter the topic name followed by the display name and click on Create topic.
    4. Click on Create Subscription.
    5. Choose the protocol, enter your email address in the endpoint box and click on Create subscription.
    6. When you receive a verification email, click on the Subscription URL to confirm the subscription.
    7. Move back to the AWS Console and select the topic that you just created. You will find a Subscription ID. Now, publish the data by clicking on Publish to topic. 
    8. Enter the subject, type the message, and click on Publish message. 
    9. Check your mailbox.

 ```

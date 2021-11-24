# Introduction-to-CloudWatch

Description
Amazon CloudWatch is a monitoring service for the resources and applications run on the AWS Cloud. 
It is used to collect and track metrics, collect and monitor log files, set alarms, and automatically react to changes in 
AWS resources.
The objective of this lab is to provide basics to get started in Amazon CloudWatch Service.

Lab Steps
Follow the steps outlined below to achieve the objective of this lab exercise:
1. Create a Linux Instance (Enable Detailed Monitoring Option)
2. Find basic metrics for the EC2 instance under Monitoring Tab
3. Create an SNS Topic 
4. Subscribe to the SNS Topic created with a protocol of email (confirm the subscription) 
5. Follow the detailed steps in this Doc for installation of CloudWatch Monitoring Metric Scripts:
https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/mon-scripts.html
6. Navigate to CloudWatch Metrics Page. Select the name space called Linux System.
7. Play with the metric options.
8. Navigate to Alarms Section and create a New Alarm
9. Select HighCPUInstance metric in the Select metric page, under Per-instance metrics.
10. Configure Thresholds required for an alarm to trigger.
11. Select the created SNS Topic to get the mail once the alarm is triggered.

Supporting References
Refer the below link for additional information:
1. https://docs.aws.amazon.com/cloudwatch/?id=docs_gateway

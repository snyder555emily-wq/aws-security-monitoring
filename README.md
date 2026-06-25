## AWS Cloud Security Monitoring Project

## Overview
Built a cloud security monitoring pipeline using AWS native security 
tools to detect and alert on threats in real time.

## Tools Used
- AWS CloudTrail — audit logging for all account activity
- AWS GuardDuty — intelligent threat detection
- AWS CloudWatch — monitoring and alerting
- AWS SNS — real time security notifications
- AWS IAM — identity and access management

## What I Built
- Enabled CloudTrail to log all API calls and account activity
- Configured GuardDuty for continuous threat detection
- Created CloudWatch alarms triggered by GuardDuty findings
- Set up SNS email alerts for immediate threat notification
- Simulated threat scenarios and validated detection pipeline
- Monitored IAM activity through CloudTrail event history

## Architecture
CloudTrail → S3 → GuardDuty Analysis → CloudWatch Alarm → SNS Alert → Email

## Key Findings
## Key Findings

### GuardDuty Findings Overview
![GuardDuty Findings](screenshots/guardduty-findings.png)

### High Severity Finding Detail
![Finding Detail](screenshots/guardduty-detail.png)

### CloudTrail IAM Activity
![CloudTrail CreateUser](screenshots/cloudtrail-create.png)
![CloudTrail DeleteUser](screenshots/cloudtrail-delete.png)

### CloudWatch Alarm Configuration
![CloudWatch Alarm](screenshots/cloudwatch-alarm.png)

### SNS Subscription Confirmed
![SNS Subscription](screenshots/sns-confirmed.png)

## What I Learned
- How AWS native security tools work together as a pipeline
- The importance of audit logging for non-repudiation in cloud environments
- How threat detection services analyze behavior patterns to identify malicious activity
- How to configure real time alerting for security events
- IAM activity monitoring and why every action needs to be logged

## Skills Demonstrated
- Cloud security architecture
- Threat detection and monitoring
- Security alerting pipelines
- IAM security monitoring
- AWS security services (CloudTrail, GuardDuty, CloudWatch, SNS)

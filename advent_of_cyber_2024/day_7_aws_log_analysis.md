# Day 7: *"Oh, no. I'M SPEAKING IN CLOUDTRAIL!"*

The Day 7 exercise focuses on utilizing **AWS CloudTrail** to monitor and investigate suspicious activity within an AWS environment. The key lessons learned include:

### 1. Understanding AWS CloudTrail
- **Definition**: AWS CloudTrail provides event logging for AWS accounts, enabling security teams to track user activity and detect anomalies.
- **Purpose**: To enhance security and compliance by providing a history of AWS API calls and related events.

### 2. Investigating Suspicious Activities
- **Log Analysis**: Reviewing CloudTrail logs to identify unauthorized or anomalous actions, such as accessing resources, creating users, or modifying permissions.
- **Key Fields**:
  - `eventSource`: Indicates the AWS service responsible for the event.
  - `userIdentity`: Details the user or entity that initiated the action.
  - `sourceIPAddress`: Provides the IP address associated with the request.

### 3. Common Threats in AWS Environments
- **Privilege Escalation**: Unauthorized users gaining elevated access rights.
- **Account Compromise**: Exploiting credentials to perform malicious actions.
- **Misconfigured Resources**: Missteps in setup leading to data exposure or security breaches.

### 4. Best Practices for AWS Security
- **Enable CloudTrail**: Ensure continuous logging for all regions.
- **Monitor Logs**: Regularly review logs for suspicious activity using SIEM tools or AWS services like CloudWatch.
- **Implement Least Privilege**: Assign users the minimum access necessary to perform their tasks.
- **Automate Responses**: Use AWS Lambda to trigger alerts or remediation actions based on CloudTrail events.

---

### Questions and Answers to Complete the Room

1. **What is the other activity made by the user glitch aside from the ListObject action?**  
   - **Answer**: PutObject

2. **What is the source IP related to the S3 bucket activities of the user glitch?**  
   - **Answer**: 53.94.201.69

3. **Based on the eventSource field, what AWS service generates the ConsoleLogin event?**  
   - **Answer**: signin.amazonaws.com

4. **When did the anomalous user trigger the ConsoleLogin event?**  
   - **Answer**: 2024-11-28T15:21:54Z

5. **What was the name of the user that was created by the mcskidy user?**  
   - **Answer**: glitch

6. **What type of access was assigned to the anomalous user?**  
   - **Answer**: AdministratorAccess

7. **Which IP does Mayor Malware typically use to log into AWS?**  
   - **Answer**: 53.94.201.69

8. **What is McSkidy's actual IP address?**  
   - **Answer**: 31.210.15.79

9. **What is the bank account number owned by Mayor Malware?**  
   - **Answer**: 2394 6912 7723 1294

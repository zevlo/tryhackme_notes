# **Day 14: Even if We're Horribly Mismanaged, There'll Be No Sad Faces on SOC-mas!**

## **Lessons Learned**

### 1. **Certificate Authority (CA) Validation**
   - **Certificates:** SSL/TLS certificates ensure secure communication and are signed by a trusted Certificate Authority (CA).
   - Understanding how to inspect a certificate and identify the issuing CA is crucial for verifying secure connections.

### 2. **Analyzing HTTP Traffic**
   - **POST Requests:** HTTP POST requests often contain sensitive data, such as credentials or form submissions.
   - Tools like **Burp Suite** or **browser developer tools** allow for inspecting HTTP traffic to uncover hidden values like passwords.

### 3. **Credential-Based Authentication**
   - Using discovered credentials to log into systems can reveal critical information, such as flags or administrative access.
   - Importance of strong and unique passwords to prevent unauthorized access.

### 4. **SOC Management and Exploitation**
   - If systems are mismanaged, attackers can escalate privileges and exploit weak controls to access administrative features.
   - Proper monitoring and strong security controls are essential to prevent malicious activities.

---

## **Questions and Answers**

1. **What is the name of the CA that has signed the Gift Scheduler certificate?**  
   `THM`

2. **Look inside the POST requests in the HTTP history. What is the password for the snowballelf account?**  
   `c4rrotn0s3`

3. **Use the credentials for any of the elves to authenticate to the Gift Scheduler website. What is the flag shown on the elves’ scheduling page?**  
   `THM{AoC-3lf0nth3Sh3lf}`

4. **What is the password for Marta May Ware’s account?**  
   `H0llyJ0llySOCMAS!`

5. **Mayor Malware finally succeeded in his evil intent: with Marta May Ware’s username and password, he can finally access the administrative console for the Gift Scheduler. G-Day is cancelled! What is the flag shown on the admin page?**  
   `THM{AoC-h0wt0ru1nG1ftD4y}`

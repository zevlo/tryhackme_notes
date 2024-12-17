# Day 2: *"One man's false positive is another man's potpourri."*

The Day 2 exercise focuses on the critical task of distinguishing between false positives and genuine security threats within a Security Operations Center (SOC). The key lessons learned include:

### 1. Understanding False Positives
- **Definition**: Alerts that indicate a threat where none exists.
- **Impact**: Can lead to wasted resources and may cause genuine threats to be overlooked.

### 2. Identifying False Positives
- **Alert Analysis**: SOC analysts must scrutinize alerts to determine their validity.
- **Data Examination**: Involves analyzing log data, understanding normal system behavior, and recognizing anomalies.

### 3. Tools and Techniques
- **SIEM Systems**: Utilizing Security Information and Event Management systems to aggregate and correlate data.
- **Threat Intelligence**: Applying threat intelligence to contextualize alerts.

### 4. Impact of False Positives
- **Alert Fatigue**: Excessive false positives can lead to alert fatigue, causing analysts to become desensitized.
- **System Tuning**: Highlights the importance of fine-tuning detection systems to minimize false positives.

### 5. Continuous Improvement
- **Detection Rules**: Regularly updating detection rules and incorporating feedback to enhance accuracy.
- **Analyst Training**: Engaging in ongoing training to stay adept at identifying and mitigating false positives.

---

### Questions and Answers to Complete the Room

1. **What is the name of the account causing all the failed login attempts?**  
   - **Answer**: service_admin

2. **How many failed logon attempts were observed?**  
   - **Answer**: 6791

3. **What is the IP address of Glitch?**  
   - **Answer**: 10.0.255.1

4. **When did Glitch successfully logon to ADM-01?**  
   - **Answer**: Dec 1, 2024 08:54:39.000

5. **What is the decoded command executed by Glitch to fix the systems of Wareville?**  
   - **Answer**: Install-WindowsUpdate -AcceptAll -AutoReboot

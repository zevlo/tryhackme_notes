# **Day 17: He Analyzed and Analyzed Till His Analyzer Was Sore!**

## **Lessons Learned**

### 1. **Log Analysis**
   - Log files are crucial for understanding system activity and identifying malicious actions.
   - Analyzing logs can reveal patterns, such as unauthorized access or attempts to delete evidence.

### 2. **Event Correlation**
   - **Correlating Events:** By analyzing logs, you can link specific events, such as login attempts, to subsequent actions like file deletions or privilege escalations.
   - Tools like SIEMs (Security Information and Event Management systems) streamline this process.

### 3. **Session Tracking**
   - **Session IDs:** Unique identifiers assigned to user sessions are critical for tracking actions performed by specific users.

### 4. **Malicious Activity Detection**
   - Regular monitoring of logs is necessary to detect and mitigate malicious activity.
   - Evidence of attackers, such as deleted CCTV footage, can be uncovered through thorough log analysis.

### 5. **Incident Response**
   - Logs provide essential evidence for post-incident investigations and can guide response strategies to prevent recurrence.

---

## **Questions and Answers**

1. **Extract all the events from the cctv_feed logs. How many logs were captured associated with the successful login?**  
   `642`

2. **What is the Session_id associated with the attacker who deleted the recording?**  
   `rij5uu4gt204q0d3eb7jj86okt`

3. **What is the name of the attacker found in the logs, who deleted the CCTV footage?**  
   `mmalware`


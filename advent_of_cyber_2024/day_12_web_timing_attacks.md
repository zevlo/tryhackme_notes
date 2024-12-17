# **Day 12: If I Can’t Steal Their Money, I’ll Steal Their Joy!**

## **Lessons Learned**

### 1. **Web Application Vulnerabilities**
   - **Logic Flaws:** Security weaknesses in application logic can allow attackers to manipulate processes, such as financial transactions, to their advantage.
   - **Broken Access Controls:** Improper user validation may permit unauthorized actions like transferring funds between accounts.

### 2. **Exploiting Transaction Manipulation**
   - By analyzing how transactions are processed, attackers can:
     - Modify critical parameters such as transfer amounts.
     - Exploit hidden logic flaws to achieve unintended outcomes.

### 3. **Importance of Input Validation**
   - Applications must enforce strong server-side validation for all user inputs to prevent tampering with critical operations.

### 4. **Capture the Flag (CTF) Approach**
   - Understand the web application workflow and locate the parameter handling the transfer value.
   - Modify the value to exceed limits (e.g., transferring over $2000) to trigger the success condition.

---

## **Questions and Answers**

1. **What is the flag value after transferring over $2000 from Glitch's account?**  
   `THM{WON_THE_RACE_007}`

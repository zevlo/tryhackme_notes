# **Day 15: Be It Ever So Heinous, There's No Place Like Domain Controller**

## **Lessons Learned**

### 1. **Domain Controller Importance**
   - The **Domain Controller (DC)** is the heart of an Active Directory (AD) environment, responsible for user authentication and enforcing security policies.
   - Compromising a DC can give attackers full control over the domain.

### 2. **Event Logs and Monitoring**
   - **Windows Event Logs** are crucial for identifying suspicious activity.
     - **Event ID 4624:** Indicates a successful login, which helps track user authentication.

### 3. **PowerShell Activity Monitoring**
   - Attackers often abuse **PowerShell** for enumeration and persistence.
   - **PowerShell Logs:** Reviewing logs can uncover commands used to enumerate users, set passwords, or manipulate the domain.

### 4. **Group Policy Object (GPO) Exploitation**
   - **GPOs:** Used to manage configurations in an Active Directory environment.
   - Malicious GPOs can be installed to maintain persistence or execute commands across the domain.

### 5. **Defense Considerations**
   - Regularly monitor event logs and PowerShell history.
   - Audit and secure Group Policy Objects.
   - Use endpoint detection tools to flag unauthorized activity.

---

## **Questions and Answers**

1. **On what day was Glitch_Malware last logged in?**  
   `07/11/2024`

2. **What event ID shows the login of the Glitch_Malware user?**  
   `4624`

3. **Read the PowerShell history of the Administrator account. What was the command that was used to enumerate Active Directory users?**  
   `Get-ADUser -Filter * -Properties MemberOf | Select-Object Name`

4. **Look in the PowerShell log file located in Application and Services Logs -> Windows PowerShell. What was Glitch_Malware's set password?**  
   `SuperSecretP@ssw0rd!`

5. **Review the Group Policy Objects present on the machine. What is the name of the installed GPO?**  
   `Malicious GPO - Glitch_Malware Persistence`

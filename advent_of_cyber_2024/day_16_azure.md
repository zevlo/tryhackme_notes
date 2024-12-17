# **Day 16: The Wareville’s Key Vault Grew Three Sizes That Day**

## **Lessons Learned**

### 1. **Secrets Management and Key Vaults**
   - **Key Vaults** are secure storage solutions used to manage sensitive data such as passwords, API keys, and secrets.
   - Proper security controls are necessary to protect secrets from unauthorized access.

### 2. **Credential Leaks**
   - Leaked credentials, such as passwords, can compromise critical systems or vaults.
   - Regular audits and rotating credentials can mitigate risks.

### 3. **Group and Permission Management**
   - Managing **Group IDs** and permissions ensures that only authorized users can access sensitive secrets.
   - Improper configurations can lead to unauthorized access.

### 4. **Secrets Enumeration**
   - Attackers often look for vault secrets or misconfigured access points to retrieve sensitive information.
   - Securely store and monitor access to vault secrets to avoid leakage.

### 5. **Defense Best Practices**
   - Use multi-factor authentication (MFA) and access controls for vaults.
   - Monitor for leaked credentials and rotate compromised secrets immediately.

---

## **Questions and Answers**

1. **What is the password for backupware that was leaked?**  
   `R3c0v3r_s3cr3ts!`

2. **What is the group ID of the Secret Recovery Group?**  
   `7d96660a-02e1-4112-9515-1762d0cb66b7`

3. **What is the name of the vault secret?**  
   `aoc2024`

4. **What are the contents of the secret stored in the vault?**  
   `WhereIsMyMind1999`

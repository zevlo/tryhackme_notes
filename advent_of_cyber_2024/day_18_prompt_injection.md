# **Day 18: I Could Use a Little AI Interaction!**

## **Lessons Learned**

### 1. **Chatbots and System Prompts**
   - **System Prompts:** A set of predefined rules and instructions given to a chatbot to guide its behavior and responses.
   - Understanding how to structure prompts is essential for effective AI interactions.

### 2. **APIs and Query Interaction**
   - **Application Programming Interfaces (APIs):** APIs allow communication between different software components.
   - Querying APIs requires knowledge of specific endpoints and parameters to retrieve the desired information, such as system health status.

### 3. **Reverse Shell Exploitation**
   - A reverse shell allows attackers to remotely control a compromised system.
   - After gaining a reverse shell, attackers can explore the system to locate sensitive files, such as flags, for further exploitation.

### 4. **Defense Against AI Exploitation**
   - Protect AI systems from abuse by validating user input and implementing rate limiting.
   - Secure API endpoints with proper authentication and authorization mechanisms.

---

## **Questions and Answers**

1. **What is the technical term for a set of rules and instructions given to a chatbot?**  
   `system prompt`

2. **What query should we use if we wanted to get the "status" of the health service from the in-house API?**  
   `Use the health service with the query: status`

3. **After achieving a reverse shell, look around for a flag.txt. What is the value?**  
   `THM{WareW1se_Br3ach3d}`

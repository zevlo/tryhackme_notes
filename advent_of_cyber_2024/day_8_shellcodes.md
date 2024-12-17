# Day 8: *"Shellcodes of the world, unite!"*

The Day 8 exercise focuses on understanding and utilizing **shellcode** to gain unauthorized access to systems, emphasizing the importance of recognizing and defending against such techniques. The key lessons learned include:

### 1. Understanding Shellcode
- **Definition**: Shellcode is a small piece of code used as the payload in the exploitation of a software vulnerability.
- **Purpose**: To provide the attacker with control over the compromised system, often by spawning a shell or executing arbitrary commands.

### 2. Crafting Shellcode
- **Assembly Language**: Shellcode is typically written in assembly language for low-level hardware interaction.
- **Encoding Techniques**: To avoid detection, shellcode may be encoded to bypass security filters.

### 3. Delivering Shellcode
- **Exploitation**: Injecting shellcode through vulnerabilities such as buffer overflows or format string attacks.
- **Social Engineering**: Embedding shellcode in malicious documents or executables to trick users into execution.

### 4. Detecting and Mitigating Shellcode Attacks
- **Intrusion Detection Systems (IDS)**: Monitoring network traffic for patterns indicative of shellcode.
- **Memory Protection Mechanisms**: Implementing technologies like Data Execution Prevention (DEP) and Address Space Layout Randomization (ASLR) to hinder shellcode execution.
- **Regular Patching**: Keeping software up to date to prevent exploitation of known vulnerabilities.

### 5. Ethical Considerations
- **Authorized Testing**: Utilizing shellcode in penetration testing requires explicit permission to ensure legal compliance.
- **Responsible Disclosure**: Reporting discovered vulnerabilities to vendors to facilitate patching and protect users.

---

### Questions and Answers to Complete the Room

1. **What is the flag value once Glitch gets reverse shell on the digital vault using port 4444?**  
   - **Answer**: AOC{GOT_MY_ACCESS_B@CK007}

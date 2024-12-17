# Day 5: *"SOC-mas XX-what-ee?"*

The Day 5 exercise focuses on understanding and mitigating **Cross-Site Scripting (XSS)** vulnerabilities, a prevalent security issue in web applications. The key lessons learned include:

### 1. Understanding Cross-Site Scripting (XSS)
- **Definition**: XSS is a security vulnerability that allows attackers to inject malicious scripts into web pages viewed by other users.
- **Impact**: Exploiting XSS can lead to unauthorized actions, data theft, and session hijacking.

### 2. Types of XSS
- **Stored XSS**: Malicious scripts are permanently stored on the target server and executed when users access the affected content.
- **Reflected XSS**: Malicious scripts are reflected off a web server, such as in error messages or search results, and executed immediately.
- **DOM-Based XSS**: The vulnerability exists in the client-side code rather than the server-side, manipulating the Document Object Model (DOM).

### 3. Identifying XSS Vulnerabilities
- **User Input Fields**: Areas where users can input data, such as forms and search bars, are common injection points.
- **URL Parameters**: Attackers can manipulate query strings to inject scripts.
- **HTTP Headers**: Headers like the Referer or User-Agent can be exploited to deliver malicious scripts.

### 4. Mitigation Strategies
- **Input Validation**: Ensure that all user inputs are validated and sanitized to prevent malicious data from being processed.
- **Output Encoding**: Encode data before rendering it on the web page to prevent the browser from interpreting it as executable code.
- **Content Security Policy (CSP)**: Implement CSP headers to restrict the sources from which scripts can be loaded and executed.
- **Security Frameworks**: Utilize frameworks that automatically escape user inputs, reducing the risk of XSS.

### 5. Importance of Regular Testing
- **Penetration Testing**: Conduct regular security assessments to identify and remediate XSS vulnerabilities.
- **Automated Scanning**: Use tools to detect XSS vulnerabilities in web applications continuously.
- **Code Reviews**: Implement thorough code review processes to catch potential vulnerabilities during development.

---

### Questions and Answers to Complete the Room

1. **What is the flag discovered after navigating through the wishes?**  
   - **Answer**: THM{Brut3f0rc1n6_mY_w4y}

2. **What is the flag seen on the possible proof of sabotage?**  
   - **Answer**: THM{m4y0r_m4lw4r3_b4ckd00rs}

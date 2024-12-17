# Day 6: *"If I can't find a nice malware to use, I'm not going."*

The Day 6 exercise focuses on understanding **Endpoint Detection and Response (EDR)** systems and their role in identifying and mitigating malware threats. The key lessons learned include:

### 1. Understanding EDR Systems
- **Definition**: EDR solutions monitor endpoints to detect, investigate, and respond to suspicious activities and security threats.
- **Purpose**: To provide real-time visibility into endpoint activities, enabling rapid detection and response to potential threats.

### 2. Malware Detection Techniques
- **Signature-Based Detection**: Identifying known malware by matching patterns against a database of signatures.
- **Behavioral Analysis**: Monitoring for abnormal behaviors that may indicate malicious activity, even if the specific malware is unknown.
- **Heuristic Analysis**: Evaluating code characteristics to identify potentially malicious intent.

### 3. Analyzing Malicious Files
- **Static Analysis**: Examining files without executing them to identify malicious indicators, such as suspicious strings or metadata.
- **Dynamic Analysis**: Executing files in a controlled environment to observe their behavior and interactions with the system.

### 4. Utilizing Analysis Tools
- **FLOSS (FireEye Labs Obfuscated String Solver)**: A tool for extracting obfuscated strings from malware, aiding in understanding its functionality.
- **Process Monitoring**: Observing running processes to detect unauthorized or suspicious activities initiated by malware.

### 5. Importance of Continuous Monitoring
- **Real-Time Alerts**: EDR systems provide immediate notifications of potential threats, allowing for swift action.
- **Incident Response**: Facilitates prompt investigation and remediation of security incidents to minimize impact.

---

### Questions and Answers to Complete the Room

1. **What is the flag displayed in the popup window after the EDR detects the malware?**  
   - **Answer**: THM{GlitchWasHere}

2. **What is the flag found in the malstrings.txt document after running floss.exe, and opening the file in a text editor?**  
   - **Answer**: THM{HiddenClue}

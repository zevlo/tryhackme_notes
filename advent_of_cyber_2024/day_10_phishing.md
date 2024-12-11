# Day 10: He had a brain full of macros, and had shells in his soul

## Overview

This task explores how cybercriminals utilize malicious macros in documents to gain access to a victim's machine. The lesson walks through identifying malicious documents, analyzing VBA macros, and exploiting them to obtain unauthorized access.

### Key Lessons

1. **Malicious Macros**:
   - Macros are small programs used to automate tasks in documents like Microsoft Word or Excel.
   - Cybercriminals often embed malicious macros in documents to execute commands and gain control over the victim's system.

2. **Analyzing Malicious Macros**:
   - Tools like `oletools` and `olevba` are used to extract and analyze macros embedded in Office documents.
   - Look for suspicious commands (e.g., `cmd.exe`, `PowerShell`) in the macro scripts.

3. **Exploitation Process**:
   - When a victim enables macros, the malicious script can execute commands like opening reverse shells or downloading additional malware.
   - Attackers can use this access to navigate the system and extract sensitive information.

4. **Mitigation Techniques**:
   - Disable macros in untrusted documents.
   - Use email filtering to block malicious attachments.
   - Educate users about the risks of enabling macros in unsolicited documents.

---

## Questions and Answers

**Q1: What is the flag value inside the flag.txt file that’s located on the Administrator’s desktop?**  
**A1: THM{PHISHING_CHRISTMAS}**

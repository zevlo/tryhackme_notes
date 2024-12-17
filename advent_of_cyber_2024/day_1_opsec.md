# Day 1: *"Maybe SOC-mas music, he thought, doesn't come from a store?"*

The Day 1 exercise introduces participants to **Operational Security (OPSEC)** principles, emphasizing the importance of protecting sensitive information from adversaries. The key lessons learned include:

### 1. Understanding Operational Security (OPSEC)
- **Definition**: A process that identifies critical information to determine if friendly actions can be observed by adversaries and then executes measures to eliminate or reduce exploitation.
- **Purpose**: To prevent adversaries from gaining access to sensitive information that could compromise operations.

### 2. Common OPSEC Mistakes
- **Metadata Exposure**: Leaving identifiable metadata in files, such as author names or software versions, which can reveal information about the creator or system.
- **Reusing Identifiers**: Using the same usernames, email addresses, or account handles across different platforms, making it easier for adversaries to link activities.
- **Inadequate Anonymity Measures**: Failing to use VPNs or proxies, leading to exposure of IP addresses and physical locations.

### 3. Investigating Malicious Files
- **Metadata Analysis**: Examining file metadata to uncover information about the creator or origin, which can aid in attribution.
- **Behavioral Analysis**: Observing the actions performed by a file, such as network connections or system changes, to identify malicious intent.

### 4. Tracking Digital Identities
- **Attribution Techniques**: Using clues from metadata, reused identifiers, and online activity to link malicious actions to specific individuals or groups.
- **OPSEC in Investigations**: Understanding how adversaries' OPSEC failures can provide leads in cyber investigations.

### 5. Enhancing Personal OPSEC
- **Best Practices**: Regularly audit personal and organizational practices to ensure sensitive information is not inadvertently exposed.
- **Continuous Improvement**: Stay informed about common OPSEC pitfalls and implement measures to mitigate them.

---

### Questions and Answers to Complete the Room

1. **Looks like the song.mp3 file is not what we expected! Run "exiftool song.mp3" in your terminal to find out the author of the song. Who is the author?**  
   - **Answer**: Tyler Ramsbey

2. **The malicious PowerShell script sends stolen info to a C2 server. What is the URL of this C2 server?**  
   - **Answer**: http://papash3ll.thm/data

3. **Who is M.M? Maybe his Github profile page would provide clues?**  
   - **Answer**: Mayor Malware

4. **What is the number of commits on the GitHub repo where the issue was raised?**  
   - **Answer**: 1

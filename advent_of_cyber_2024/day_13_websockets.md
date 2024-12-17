# **Day 13: It Came Without Buffering! It Came Without Lag!**

## **Lessons Learned**

### 1. **Buffer Overflow Attacks**
   - **Buffer Overflow:** A vulnerability that occurs when a program writes more data to a buffer than it can handle, causing adjacent memory to be overwritten.
   - Attackers can exploit buffer overflows to:
     - Crash a program.
     - Inject and execute malicious code.
     - Manipulate application behavior.

### 2. **Identifying Vulnerabilities**
   - Understanding how buffers are handled in memory is crucial.
   - Tools like `gdb` (GNU Debugger) can help analyze memory and identify vulnerable areas.

### 3. **Crafting Exploits**
   - By sending a specially crafted payload, attackers can control program execution.
   - This involves:
     - Locating the buffer’s memory location.
     - Injecting values to trigger the overflow.

### 4. **Mitigations**
   - Implementing secure coding practices, such as:
     - Proper input validation.
     - Avoiding unsafe functions like `strcpy()` in C/C++.
     - Using modern protections like ASLR (Address Space Layout Randomization) and DEP (Data Execution Prevention).

---

## **Questions and Answers**

1. **What is the value of Flag1?**  
   `THM{dude_where_is_my_car}`

2. **What is the value of Flag2?**  
   `THM{my_name_is_malware._mayor_malware}`

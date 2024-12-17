# **Day 11: If You'd Like to WPA, Press the Star Key!**

## **Lessons Learned**

### 1. **Wireless Network Fundamentals**
   - **WPA (Wi-Fi Protected Access):** A widely used wireless network security protocol that relies on a Pre-Shared Key (PSK) for authentication.
   - **BSSID:** The MAC address of a wireless access point or device.
   - **SSID:** The name of the wireless network.

### 2. **Capturing WPA Handshakes**
   - A WPA handshake occurs when a device connects to a WPA-protected network. By capturing this handshake, attackers can attempt to crack the network password (PSK).
   - **Tools and Workflow:**
     - Use `airmon-ng` to enable **monitor mode** on a wireless interface.
     - Use `airodump-ng` to scan for networks, identify SSIDs, and capture WPA handshakes.
     - Force a client to reconnect by deauthentication attacks to speed up the handshake capture.

### 3. **Cracking the PSK**
   - Once the handshake is captured, tools like `aircrack-ng` can brute-force the handshake using a wordlist to determine the correct Pre-Shared Key.

---

## **Questions and Answers**

1. **What is the BSSID of our wireless interface?**  
   `02:00:00:00:02:00`

2. **What is the SSID and BSSID of the access point? Format: SSID, BSSID**  
   `MalwareM_AP, 02:00:00:00:00:00`

3. **What is the BSSID of the wireless interface that is already connected to the access point?**  
   `02:00:00:00:01:00`

4. **What is the PSK after performing the WPA cracking attack?**  
   `fluffy/champ24`

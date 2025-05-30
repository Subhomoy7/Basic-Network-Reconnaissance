# Basic-Network-Reconnaissance
Basic information about network reconnaissance.<br>
Author - Subhomoy Mitra. <br>
This project demonstrates how to use **Nmap** to scan your local network for open ports and identify potential security risks. The objective is to understand basic network reconnaissance, recognize active hosts, and learn about commonly exposed services that may pose a threat.

## 📌 Objectives

- Discover active devices on a local network
- Identify open TCP ports using a SYN scan
- Research services running on discovered ports
- Analyze packet capture with Wireshark (optional)
- Evaluate potential security risks from open ports
- Document and save scan results

## 🛠️ Steps Followed

1. **Install Nmap**  
   Download and install Nmap from the [official website](https://nmap.org/download.html).

2. **Identify Local IP Range**  
   Find your subnet (e.g., `192.168.0.0/24`) using `ipconfig` (Windows) or `ifconfig/ip a` (Linux/macOS).

3. **Run TCP SYN Scan**  
   ```bash
   nmap -sS 192.168.0.0/24

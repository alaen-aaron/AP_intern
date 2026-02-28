# AP_intern
# Cybersecurity Internship - Task 1

## Lab Environment Setup

Attacker Machine:
Kali Linux

Target Machine:
Metasploitable 2

Network:
Host-Only Adapter (VirtualBox)

Kali IP:
192.168.56.102

Metasploitable IP:
192.168.56.104

---

## Lab Demonstrations

### 1. Network Communication

Tested connectivity using ping.

Command:
ping 192.168.56.104

---

### 2. Port Scanning

Used Nmap to scan the target machine.

Command:
nmap 192.168.56.104

Discovered open ports:

21 - FTP  
22 - SSH  
23 - Telnet  
25 - SMTP  
53 - DNS  
80 - HTTP  
139 - NetBIOS  
445 - SMB  
3306 - MySQL  
5432 - PostgreSQL  
5900 - VNC  

---

### 3. Packet Analysis

Captured ICMP packets using Wireshark while performing a ping test.

---

### 4. Linux Fundamentals

Commands demonstrated:

pwd  
mkdir  
cd  
touch  
chmod  
ls -l  

---

### 5. Cryptography Demonstration

Encrypted and decrypted a message using OpenSSL.

Commands used:

openssl enc -aes-256-cbc -salt -in msg.txt -out encrypted.txt

openssl enc -aes-256-cbc -d -in encrypted.txt -out decrypted.txt

---

## Tools Used

- Kali Linux
- Metasploitable 2
- Nmap
- Wireshark
- OpenSSL
- VirtualBox

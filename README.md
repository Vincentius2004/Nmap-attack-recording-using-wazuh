# Nmap-attack-recording-using-wazuh

## 1. PING EACH MACHINE TO OTHER MACHINE

### A.Kali Linux (Attacker)
![Kali Linux](foto/Kali-ping.png)

### B.Honeypot Ubuntu
![Honeypot Ubuntu](foto/honeypot-ping.png)

### C.Wazuh Manager
![Wazuh Manager](foto/wazuh-ping.png)


## 2. Nmap ATTACK TEST
nmap -a 192.168.1.100
![Kali Linux](foto/Kali-nmap.png)


## 3. WAZUH DASHBOARD LOGS
![Kali Linux](foto/logs.png)

## 4. WAZUH DASHBOARD DISPLAY
![Kali Linux](foto/dashboard.png)


## 5. WIRESHARK DISPLAY
Using (ip.src == 192.168.1.10) && (tcp || udp || icmp)
![Kali Linux](foto/wireshark.png)

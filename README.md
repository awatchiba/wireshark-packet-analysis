# Wireshark Packet Analysis

This is a small project where I used Wireshark to capture and look at basic network traffic from my computer.  
The goal was just to get familiar with how packets look and how to filter different protocols.

---

## What’s in this project

### **captures/**
All the Wireshark files I saved:
- `full_capture` – short recording of everything  
- `dns_capture` – DNS lookups  
- `arp_capture` – ARP traffic on my Wi-Fi  
- `tcp_handshake_capture` – shows the start of a connection  
- `https_capture` – encrypted HTTPS traffic  

### **screenshots/**
Screenshots of what each filtered capture looked like in Wireshark.
<img width="1440" height="900" alt="https" src="https://github.com/user-attachments/assets/290335da-89e8-4ee5-99df-3664b0f1e556" />
<img width="1440" height="900" alt="full_capture" src="https://github.com/user-attachments/assets/6aaa39af-1a91-423f-8d52-12498d0d0cc8" />
<img width="1440" height="900" alt="tcp_handshake" src="https://github.com/user-attachments/assets/1e360a91-f064-48b1-97a5-fa6a71a99cee" />
<img width="1440" height="900" alt="arp" src="https://github.com/user-attachments/assets/c4bf02a1-4fff-461c-b9c2-426458b27b55" />
<img width="1440" height="900" alt="dns" src="https://github.com/user-attachments/assets/0393475f-3021-40a3-9ecf-a59570d22c4c" />


---

## What I did

- Opened Wireshark  
- Captured a few seconds of traffic  
- Visited simple sites to generate packets  
- Used filters like `dns`, `arp`, `tcp.flags.syn == 1`, and `tls`  
- Saved the captures + took screenshots  

---

## What I learned

- DNS = finding website IPs  
- ARP = devices finding each other  
- TCP handshake = connection starting  
- HTTPS = encrypted traffic  
- Even short captures show a lot happening behind the scenes  

---

## About

This was a beginner networking/cybersecurity assignment to help me understand how Wireshark works and what common protocols look like.

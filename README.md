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

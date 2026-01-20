# Lab Environment

This lab was conducted in a controlled virtualized environment to simulate real-world post-breach offline password attack scenarios.

---

## Systems Used

- **Kali Linux**  
  Role: Attacker machine used for offline password cracking  
  Tools: Hashcat, rockyou.txt, custom rules and masks

- **Ubuntu Linux**  
  Role: Password hash generation and storage  
  Tools: mkpasswd, core Linux utilities

---

## Tooling Overview

- **Hashcat** – Offline password cracking framework
- **rockyou.txt** – Common leaked password wordlist
- **mkpasswd** – Secure password hash generation utility
- **Linux CLI tools** – File handling and transfer simulation

---

## Purpose of the Environment

The environment mirrors a realistic breach scenario where an attacker gains access to hashed credentials and attempts offline cracking.

All activities were performed strictly for educational and defensive learning purposes.

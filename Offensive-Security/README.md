# TryHackMe: Intro to Offensive Security (Pre-Security Path)

## Room Overview

This room introduces the fundamentals of offensive security, where the goal is to simulate cyberattacks in a controlled environment to identify vulnerabilities.
It focuses on ethical hacking, penetration testing, and learning how attackers think — so defenders can build better defenses.

---

## Key Learnings

### ⚔️ Offensive Security Concepts

- Definition: Simulating real-world cyberattacks to find and fix security flaws.
- Goal: Strengthen systems by identifying weaknesses before attackers do.
- Difference from Defensive Security: Defensive secures systems; offensive tests their security through simulated attacks.

---

## Hands-On Exercise: Hack a Bank (Simulation Through TryHackMe)

### Target: `http://fakebank.thm`

- Tool Used: gobuster for directory brute-forcing.
- Objective: Discover hidden paths and perform an unauthorized (simulated) bank transfer.

### Steps Performed:
gobuster -u http://fakebank.thm -w wordlist.txt dir 
Successfully got the flag:
BANK-HACKED

---

## 📸 Practical Demonstration Screenshots

### Step 1: Gobuster Directory Brute Force  
![Step 1](https://github.com/user-attachments/assets/b95a4649-452d-41b6-bc42-10e8221f2796)

### Step 2: Transfer Page (Simulation)  
![Step 2](https://github.com/user-attachments/assets/06bba031-b762-428d-84be-5b00c0c2250b)

### Step 3: Successful Exploit (Simulation)
![Step 3](https://github.com/user-attachments/assets/67327649-56f5-4a1b-9d0c-6fe15751a39a)


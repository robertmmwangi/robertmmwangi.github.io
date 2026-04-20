---
title: "Lab Challenges"
permalink: /labs/
layout: single
author_profile: true
---

## 🧪 My Hands-On Journey Through Cybersecurity Labs

I believe in learning by doing. These labs are my proof. Each one challenged me. Each one taught me something I will use in a real SOC.

---

### 1.0 Introduction to Log Analysis 📊

**Platform:** TryHackMe  
**When I did it:** April 2026

**The problem:**

A system was compromised. How would I know? Where would I look? The answer was in the logs. But logs are noisy. I had to find the signal in the static.

**My approach:**

I reviewed system logs across multiple endpoints. I looked for anomalies. I correlated events. I asked myself: what does normal look like? Then I looked for anything that did not fit.

<div style="background: #f0f7ff; padding: 15px; border-radius: 10px; margin: 15px 0;">
  <strong>🛠️ Tools:</strong> TryHackMe lab environment, pattern recognition<br>
  <strong>💡 The lesson:</strong> Logs are the eyes and ears of a SOC analyst. Without them, you are blind. With them, you can trace an attacker every move. But only if you know what to look for.
</div>

*📸 Screenshot placeholder*

---

### 2.0 L2 MAC Flooding and ARP Spoofing 🔀

**Platform:** TryHackMe  
**When I did it:** April 2026

**The problem:**

Network attacks happen at layers most people never see. How does ARP spoofing work? Why does MAC flooding confuse switches?

**My approach:**

I set up a controlled environment. I simulated ARP spoofing. I watched traffic redirect before my eyes. I analyzed packets before and after the attack. Then I researched how to detect and stop it.

<div style="background: #f0f7ff; padding: 15px; border-radius: 10px; margin: 15px 0;">
  <strong>🛠️ Tools:</strong> TryHackMe virtual environment, Wireshark concepts<br>
  <strong>💡 The lesson:</strong> Trust on a network is dangerous. ARP has no authentication. That is a feature for attackers and a nightmare for defenders. The only solution is constant monitoring and segmentation.
</div>

*📸 Screenshot placeholder*

---

### 3.0 DNS In Detail 🌐

**Platform:** TryHackMe  
**When I did it:** April 2026

**The problem:**

DNS is the phonebook of the internet. But what happens when someone poisons the phonebook?

**My approach:**

I studied the DNS hierarchy. I learned about record types: A, AAAA, CNAME, MX, TXT. Then I explored attack vectors like DNS spoofing and tunneling.

<div style="background: #f0f7ff; padding: 15px; border-radius: 10px; margin: 15px 0;">
  <strong>🛠️ Tools:</strong> TryHackMe lab, DNS analysis<br>
  <strong>💡 The lesson:</strong> DNS is often overlooked. Attackers love overlooked things. A TXT record can exfiltrate data right under your nose. DNSSEC is not optional anymore.
</div>

---

### 4.0 Metasploit Framework 🔨

**Platform:** Cyber Shujaa / TryHackMe  
**When I did it:** April 2026

**The problem:**

Metasploit is famous. But fame does not teach you how to use it. I had to learn.

**My approach:**

I launched `msfconsole`. I scanned a target. I searched for vulnerabilities. I selected an exploit. I ran it in a lab environment. Then I documented everything.

<div style="background: #f0f7ff; padding: 15px; border-radius: 10px; margin: 15px 0;">
  <strong>🛠️ Tools:</strong> Metasploit Framework, Nmap<br>
  <strong>💡 The lesson:</strong> Metasploit is a powerful tool. But power without responsibility is dangerous. I learned to use it so I can defend against it. That is the ethical hacker way.
</div>

*📸 Screenshot placeholder*

---

### 5.0 Attacking Web Applications with FFUF 🎯

**Platform:** Cyber Shujaa  
**When I did it:** April 2026

**The problem:**

Web applications hide endpoints. Attackers love hidden endpoints. How do you find them?

**My approach:**

I used FFUF (Fuzz Faster U Fool). I fed it wordlists. It found directories I did not know existed. I analyzed response codes to separate valid paths from noise.

<div style="background: #f0f7ff; padding: 15px; border-radius: 10px; margin: 15px 0;">
  <strong>🛠️ Tools:</strong> FFUF, SecLists wordlists<br>
  <strong>💡 The lesson:</strong> Fuzzing reveals secrets. A developer hides an admin panel. FFUF finds it in seconds. That is why rate limiting and authentication matter.
</div>

---

### 6.0 OWASP Top 10 (2025) 📖

**Platform:** Cyber Shujaa  
**When I did it:** April 2026

**The problem:**

The OWASP Top 10 is the industry standard. But reading a list is not the same as understanding it.

**My approach:**

I studied each category. I performed simulated testing for common vulnerabilities. I documented mitigation strategies for each one.

<div style="background: #f0f7ff; padding: 15px; border-radius: 10px; margin: 15px 0;">
  <strong>📚 Topics covered:</strong>
  <ul>
    <li>Broken Access Control</li>
    <li>Cryptographic Failures</li>
    <li>Injection (SQL, NoSQL, OS Command)</li>
    <li>Security Misconfiguration</li>
    <li>Vulnerable and Outdated Components</li>
  </ul>
  <strong>💡 The lesson:</strong> The OWASP Top 10 is not a checklist. It is a mindset. Every web application has weak points. Your job is to find them before the bad guys do.
</div>

---

## 🛠️ Tools I Have Mastered Along the Way

<div style="display: flex; flex-wrap: wrap; gap: 10px; margin: 20px 0;">
  <span style="background: #0077b5; color: white; padding: 8px 18px; border-radius: 25px;">🔨 Metasploit</span>
  <span style="background: #0077b5; color: white; padding: 8px 18px; border-radius: 25px;">🎯 FFUF</span>
  <span style="background: #0077b5; color: white; padding: 8px 18px; border-radius: 25px;">📡 Wireshark</span>
  <span style="background: #0077b5; color: white; padding: 8px 18px; border-radius: 25px;">💻 TryHackMe</span>
  <span style="background: #0077b5; color: white; padding: 8px 18px; border-radius: 25px;">📊 Log Analysis</span>
  <span style="background: #0077b5; color: white; padding: 8px 18px; border-radius: 25px;">🔍 Nmap</span>
  <span style="background: #0077b5; color: white; padding: 8px 18px; border-radius: 25px;">📖 OWASP</span>
  <span style="background: #0077b5; color: white; padding: 8px 18px; border-radius: 25px;">💉 SQL Injection</span>
</div>

---

## 📈 Lab Progress Summary

<div style="display: flex; flex-wrap: wrap; gap: 15px; margin: 20px 0;">
  <div style="flex: 1; min-width: 180px; background: #e8f4f8; padding: 15px; border-radius: 10px;">
    <div style="font-weight: bold;">📊 Log Analysis</div>
    <div>TryHackMe</div>
    <div style="color: green;">✅ Completed</div>
  </div>
  <div style="flex: 1; min-width: 180px; background: #e8f4f8; padding: 15px; border-radius: 10px;">
    <div style="font-weight: bold;">🔀 ARP Spoofing</div>
    <div>TryHackMe</div>
    <div style="color: green;">✅ Completed</div>
  </div>
  <div style="flex: 1; min-width: 180px; background: #e8f4f8; padding: 15px; border-radius: 10px;">
    <div style="font-weight: bold;">🌐 DNS In Detail</div>
    <div>TryHackMe</div>
    <div style="color: green;">✅ Completed</div>
  </div>
  <div style="flex: 1; min-width: 180px; background: #e8f4f8; padding: 15px; border-radius: 10px;">
    <div style="font-weight: bold;">🔨 Metasploit</div>
    <div>Cyber Shujaa</div>
    <div style="color: green;">✅ Completed</div>
  </div>
</div>

---

## 🚀 What Comes Next

I am not stopping here. My lab journey continues:

- ⬜ Splunk: Exploring SPL (in progress)
- ⬜ Red Team Recon (next on my list)
- ⬜ Windows Forensics 2
- ⬜ Malware Analysis Deep Dive

---

## 🤝 Want to Follow My Journey?

Connect with me on [LinkedIn](https://linkedin.com/in/robert-mbuthia) or check my [GitHub](https://github.com/robertmmwangi). I post about every lab I complete.

<div style="text-align: center; margin: 30px 0;">
  <a href="/" style="background: #0077b5; color: white; padding: 10px 25px; border-radius: 25px; text-decoration: none;">🏠 Back to Home</a>
</div>

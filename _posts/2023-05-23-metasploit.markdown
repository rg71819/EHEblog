---
layout: post
title:  "Metasploit for beginners"
date:   2023-05-14 05:28:23 -0500
author: Ravi Shankar Gurram
categories: ['Assessment Tools']
background: '/images/Home page Background.jpg'
---

## Metasploit for beginners

Metasploit is a powerful and widely-used open-source exploitation framework written in Ruby. The Metasploit Framework is a community version available for free. There is also a commercial version “Metasploit Pro” with additional features. Metasploit is available in both GUI and command line versions, GUI version is called Armitage. Metasploit framework consists of multiple modules that help security professionals identify and exploit vulnerabilities in systems and applications. A module is a piece of software that the Metasploit Framework uses for tasks like exploiting and scanning targets. Metasploit Framework provides modules that can be used in all phases of penetration testing from information gathering to post-exploitation. 

Tools in Metasploit Framework:
- Msfconsole: Msfconsole is the default Metasploit interface that provides all the commands needed to interact with the framework.
- Msfdb: Msfdb is a database that stores information, including host data and exploit results. We can also import data from external tools like Nmap.
- Msfvenom: The MSFvenom tool allows you to create custom payloads for different targets.
- Meterpreter: Meterpreter is an advanced Metasploit payload that provides an interactive shell for the attacker to explore the target machine and execute code.

Metasploit Framework consists of following modules:
- Exploits: This module provides exploits that are used to target known vulnerabilities in software and systems.
- Payloads: Payloads are codes that will run on the target system after exploiting the vulnerability to perform certain task like accessing data.
- Auxiliary: This Module includes Scanners, Fuzzers
- Encoders: These are modules that can be used to obfuscate the exploit code to make it more difficult to detect.
- Evasion: It allows users to generate evasive payloads without installing external tools and provides a framework for developers to build their own evasion modules.
- Post: Post modules are useful in the post-exploitation stage of penetration testing, like pivoting to another target or gathering more information.
- NOP: A NOP module (No Operation) is often used to achieve consistent payload sizes.

## Installation Process

- Metasploit is preinstalled in security-based Linux distros like parrot and kali Linux.
- You can use the documentation provided to install Metasploit on Windows, Linux and MacOS
https://docs.rapid7.com/metasploit/installing-the-metasploit-framework/#Installation 
- For Debian and Ubuntu based Linux distros
  - apt install metasploit-framework
- For CentOS/Redhat
  - yum install metasploit-framework

## Metasploit Usage

<iframe width="640" height="480" src="https://www.youtube.com/embed/XJ1qDUScn3w" frameborder="0" allowfullscreen></iframe>

## Additional Resources

- Metasploit Documentation: https://docs.rapid7.com/metasploit/installing-the-metasploit-framework/ 
- Metasploit Unleashed – Free Ethical Hacking Course by offensive security https://www.offsec.com/metasploit-unleashed/
- TryHackMe room to practice Metasploit: https://tryhackme.com/room/metasploitintro

---
layout: post
title:  "Sysinternals for beginners"
date:   2023-08-14 05:28:23 -0500
author: Safwat
categories: ['Miscellaneous Tools']
background: '/images/Home page Background.jpg'
---
## Sysinternals for beginners
Sysinternals is a collection of advanced system utilities developed by Microsoft. These tools are designed to help troubleshoot, monitor, and analyze the Windows operating system. Sysinternals tools provide deep insights into the inner workings of Windows, allowing users to understand and manage various aspects of the system.
The Sysinternals Suite is a set of over 70 advanced diagnostic and troubleshooting utilities for the Microsoft Windows platform. These utilities can be classified into various groups as shown below:
- **Files and Disk Utilities**: Acceschk, AccessEnum, Cacheset, contig, Disk2vhd, DiskExt, DiskMon, DiskView, Disk Usage,EFSDump, LDMDump, MoveFile, NTFSInfo, PageDefrag, PendMoves, SDelete, RegMon, Sigcheck,Streams, Sync, VolumelD, etc.
- **Networking Utilities**: AD Explorer, AD Insight, AdRestore, PipelList, PsFile, PsPing, ShareEnum, TCPView, Whois.
- **Process Utilities**: Autoruns, Handle, ListDLLs, PortMon, ProcDump, Process Explorer, Process Monitor, PsExec,PsGetSid, PsKill, PsList, PsService, PsSuspend, PsTools, ShellRunas, VMMap, etc.
- **Security Utilities**: Autologon, , LogonSessions, NewSID, PsLoggedOn, PsLogList, Rootkit Revealer, Sysmon, etc.
- **System Information**: ClockRes, Coreinfo, Livekd, LoadOrder, ProcFeatures, Psinfo, RAMMap, WinObj, etc.
- **Miscellaneous**: Bginfo, Bluescreen Screen Saver, Cpustres, Ctrl2Cap, DebugView, Desktops, Hex2dec,NotMyFault, PsPasswd, PsShutdown, RegDelNull, Registry Usage, Reghide, Reglump, Strings, Testlimit, Zoomlt, etc.

While Sysinternals is not explicitly designed for cybersecurity, several Sysinternals tools can be useful in various cybersecurity scenarios. Here are a few examples:
- **Process Explorer**: Process Explorer provides detailed information about running processes, including their dependencies, loaded DLLs, and network connections. It can be valuable for identifying malicious processes, investigating suspicious activities, and analyzing the behavior of potentially harmful applications.
- **Autoruns**: Autoruns helps you manage the programs that automatically start on Windows boot. This tool can be used to detect and disable malicious auto-start entries, such as malware or rootkits, which often abuse the automatic startup mechanism to maintain persistence on the system.
- **TCPView**: TCPView displays real-time information about TCP and UDP endpoints on a Windows system. It can be used to identify network connections established by processes, helping to detect unauthorized or suspicious network activity, such as connections to known malicious IP addresses
- **Procmon**: Process Monitor (Procmon) enables you to capture and analyze system events, including file system activity, registry changes, network events, and more. It can assist in understanding the behavior of malware, identifying unauthorized changes, and monitoring system activity during incident response.
- **AccessChk and AccessEnum**: These tools help in assessing and auditing permissions and access control settings within the Windows file system, registry, and Active Directory. They can be used to identify insecure or misconfigured access controls that could potentially lead to security vulnerabilities.
- **PsExec**: PsExec allows you to execute processes remotely on Windows systems. While it can have legitimate administration purposes, it can also be abused by attackers for lateral movement or remote execution of malicious code. Monitoring for PsExec usage can be a part of a comprehensive cybersecurity strategy.

## Uses of Sysinternals
Sysinternals tools are widely used for various purposes related to system troubleshooting, monitoring, and analysis. Here are some common uses of Sysinternals tools:
 - **Troubleshooting System Issues**: Sysinternals tools like Process Explorer, Process Monitor, and Autoruns are commonly used to diagnose and troubleshoot system problems. They help identify resource-hungry processes, analyze system behavior, track down application errors, and detect malware or unwanted software.
- **Malware Analysis**: Sysinternals tools are valuable for analyzing and understanding the behavior of malware. Tools like Process Explorer, Procmon, and TCPView can help security analysts identify malicious processes, monitor network connections initiated by malware, and capture system events related to malware activities.
- **System Monitoring and Performance Analysis**: Sysinternals tools provide detailed insights into system performance and resource utilization. Tools like Process Explorer, Process Monitor, and RAMMap help monitor CPU, memory, disk, and network usage. They can assist in identifying resource bottlenecks, troubleshooting performance issues, and optimizing system performance.
- **Security Analysis and Auditing**: Sysinternals tools like AccessChk, AccessEnum, and ShareEnum are useful for security analysis and auditing. These tools help assess and audit file system permissions, registry settings, and access control configurations. They assist in identifying security vulnerabilities, misconfigurations, and unauthorized access permissions.
- **Software and System Configuration Management**: Sysinternals tools such as Autoruns, Regmon, and Disk2vhd aid in managing software and system configurations. Autoruns helps manage auto-start programs, Regmon monitors registry activity, and Disk2vhd allows creating virtual hard disk images of physical systems for backup or virtualization purposes.
- **Incident Response and Forensics**: Sysinternals tools are valuable in incident response and forensic investigations. Tools like Process Explorer, Procmon, and Disk Usage can assist in identifying and analyzing malicious activities, tracking system changes, and recovering deleted files or system artifacts.

## SYSInternals Installation Video

<iframe src="https://drive.google.com/file/d/1j4-8396AXuAJfnI1Ll9QNGVAdbsjoskQ/preview" width="640" height="480" allow="autoplay"></iframe>

## SYSInternals Explanation Video

<iframe src="https://drive.google.com/file/d/1Z4-Ncvk4jZ5saofU0gORqRJTTuOw9Xjg/preview" width="640" height="480" allow="autoplay"></iframe>

## Additional Resources
- [https://learn.microsoft.com/en-us/sysinternals/downloads/security-utilities](https://learn.microsoft.com/en-us/sysinternals/downloads/security-utilities)
- [https://download.sysinternals.com/files/SysinternalsMalwareCleaning.pdf](https://download.sysinternals.com/files/SysinternalsMalwareCleaning.pdf)


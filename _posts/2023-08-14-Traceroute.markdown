---
layout: post
title:  "Traceroute for beginners"
date:   2023-08-14 05:28:23 -0500
author: Safwat
categories: ['Miscellaneous Tools']
background: '/images/Home page Background.jpg'
---

## Traceroute for beginners
- Traceroute or tracert is a command that runs network diagnostic functionality on computer operating systems.
- In general, both commands work the same. The difference lies in the operating system – while Linux and macOS use the traceroute command, Windows utilizes tracert.
- The traceroute command sends three probe packets through the network and monitors how they reach the destination.
- A probe packet will then go through multiple devices such as routers and switches to reach the target IP address in a process called a hop. The traceroute command maps each hop within the route along with its round-trip-time (RTT).
- The log may also include other details such as each hop’s device name and IP address.

## Uses of Traceroute
- A traceroute provides a map of how data on the internet travels from its source to its destination. When you connect with a website, the data you get must travel across multiple devices and networks along the way, particularly routers.
- It can be a useful tool for cybersecurity professionals to analyze network paths, identify potential bottlenecks, and investigate network connectivity issues. 
## Installation

## For Linux:
The traceroute is not a default utility of the Linux system. To use the traceroute, we need to install it manually if it is not installed already. To install it, execute one of the following commands:
- `sudo apt install inetutils-traceroute`
- `sudo apt install traceroute`

<iframe src="https://drive.google.com/file/d/14n-xZofs_p7AXQyXAgTNNm1UheF0xqBF/preview" width="640" height="480" allow="autoplay"></iframe>

In Windows and Mac system tracert and traceroute are the default tool , respectively. It is not required to install additionally.

## Steps to Run Traceroute/tracert 
#### On Mac/Linux:
- Open up an instance of Terminal.
- Type in the phrase “`traceroute [hostname]`” and press Enter.
    - `traceroute www.google.com`
#### On Windows:
- Go to the Start menu.
- Select Run.
- Type in “`cmd`” and then hit “OK.” This initiates a command prompt.
- Type in “`tracert [hostname]`” and press Enter
    - `tracert www.google.com`

## Traceroute Usage


<iframe src="https://drive.google.com/file/d/13gVJU7bmW92QQJQCWy5mk7wJdSRYvcVb/preview" width="640" height="480" allow="autoplay"></iframe>

## Additional Resources
- [https://www.javatpoint.com/linux-traceroute](https://www.javatpoint.com/linux-traceroute) 


---
title: Setting up a Hyper-V Virtual Lab
author: Michael Groesbeck
date: '2019-06-12'
slug: setting-up-a-hyper-v-virtual-lab
categories: []
description: 'Some detail about setting up a virtual lab in Windows 10 with Hyper-V'
tags:
  - InfoSec
  - Hyper-V
---

## Notes about setting up a virtual lab

I've be going through the book [Building Virtual Machine Labs](https://leanpub.com/u/da_667) and will eventually write up more of the lab setup process. But for now I wanted to save other resources I found helpful while going through the book. 

I set up the pfSense virtual machine, added rules in the web interface, and set up the Squid Proxy server in the Squid package. With the proxy server enabled, I had to add the details to the Kali Linux and Ubuntu Server virtual machines. 

The answer to [this question](https://askubuntu.com/questions/175172/how-do-i-configure-proxies-without-gui) on Ask Ubuntu was very helpful in getting the necessary system wide proxies in order.


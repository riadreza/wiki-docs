---
title: Ubuntu
description: 
published: true
date: 2025-12-17T09:11:54.894Z
tags: linux, ubuntu
editor: markdown
dateCreated: 2025-12-17T07:47:32.303Z
---

# Ubuntu

Ubuntu is a free, open-source Linux operating system built on Debian. It’s designed to be **easy to use, reliable, and secure**. People use Ubuntu on everything from personal computers to servers and even cloud platforms, making it a versatile choice for both beginners and professionals.

---

## Important Commands:
Some important commands are given below.

### Enable root access:
Enable root user to SSH access in Ubuntu:

```bash
sudo sed -i 's/#PermitRootLogin prohibit-password/PermitRootLogin yes/' /etc/ssh/sshd_config
```

```bash
sudo systemctl restart ssh
```

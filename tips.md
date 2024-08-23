---
permalink: TIPS/
---

# TIPS

- Tip#1: Use sudo to do root commands without logging to root. Example: sudo poweroff

### Steps to setup sudo:

### 1. Log in as root using `su -` command.

### 2. Type in this command `sudo usermod -aG sudo username` (change username with your own username).

### 3. Reboot the system/virtual machine.

### 4. Check if sudo is added using `groups username` command.

### 5. Everytime sudo is used, you need to type your own username password.

### One benefit of sudo is it reduces the number of root access to increase security.

- Tip#2: Null

<br>

#### Acknowledgement(s):

#### -cbkadal's os242/tips.md

#### -chatGPT

<hr>

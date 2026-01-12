# UltimatePhishing-python
This repository contains a Python-based phishing tool designed for security researchers, penetration testers, and students. 

# Key Features
Automated Page Cloning: Quickly mirrors login interfaces for testing.

Credential Logging: Securely captures input for analysis during authorized audits.

Email Integration: Templates for simulating phishing outreach.

Reporting: Generates data on "click-through" rates to measure user awareness.

**⚠️ Mandatory Disclaimer (Terms of Use)**
Warning: This tool is strictly for educational and ethical security testing purposes only.

Using this tool against targets without prior formal consent is illegal. It is the end user's responsibility to obey all applicable local, state, and federal laws. The author assumes no liability and is not responsible for any misuse or damage caused by this program.

By using this software, you agree to:

Only use it on systems you own or have explicit written permission to test.

Never use it for financial gain or malicious intent.

Promote cybersecurity awareness and defense.

# Installation & Usage
To set up the environment for educational testing:

```bash
sudo apt update
```
```bash
apt install curl
```
```bash
apt install openssl
```
```bash
sudo apt install git python3 python3-pip php openssh-client -y
```
```bash

```
```bash
cd UltimatePhishing-python
```
```bash
pip3 install -r files/requirements.txt
```
if error comes,try this command:
```bash
pip3 install -r files/requirements.txt --break-system-packages
```
```bash
python3 phish.py
```

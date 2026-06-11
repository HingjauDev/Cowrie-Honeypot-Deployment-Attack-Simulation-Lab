# Cowrie-Honeypot-Deployment-Attack-Simulation-Lab
A learning purpose homelab simulation

This repository documents the setup , network configuration and attack simulation of a Cowrie SSH/Telnet Honeypot deployed on an Ubuntu VM, attacked via a Kali Linux VM within a controlled Oracle VirtualBox environment. 

## Prerequisites & Baseline Setup

The following components are the baseline environment for the network redirection configuration:
* **Attacker Note:** A standard instance of Kali Linux configured with standard penetration testing tools (`nmap`, `hydra`).
* **Honeypot Node:** A fresh deployment of Ubuntu Server.
* **Honeypot Software:** Cowrie installed under a dedicated, non-root system user (`cowrie`) following standard deployment practices, initially listening on the default non-privileged port `2222`.

## 🎯 Project Overview & Goal

The goal of this project is understanding how to setup a honeypot to trap an attacker for log analysis, mastering internal network architecture and traffic redirection using `iptables`, and analyzing adversary behavior using tools like `nmap` and `hydra`.

By simulating the entire attack lifecycle within a controlled Oracle VirtualBox environment, this project demonstrates both the defensive engineering required to safely capture threat intelligence and the offensive techniques used to validate security controls.
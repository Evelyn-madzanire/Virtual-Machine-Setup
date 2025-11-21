# 🏠 Home Lab: Ubuntu Server VM on VMware

## 📖 About
This repository documents my personal **home lab setup** using **VMware** and **Ubuntu Server**.  
It includes step-by-step instructions, screenshots, and configurations for **learning, testing, and experimentation**.

## 🎯 Purpose
- Learn Ubuntu Server administration  
- Test networking, services, and server configurations safely  
- Build a portfolio of home lab projects

## 🛠 Prerequisites
- VMware Workstation/Player installed  
- Ubuntu Server ISO downloaded  
- At least 2 GB RAM and 20 GB disk space for the VM

## 🖱 VM Setup Overview
1. **Create a New VM in VMware**  
   - Assign resources, select ISO, and name your VM  
2. **Install Ubuntu Server**  
   - Configure network, create user, and select packages  
3. **Post-Installation Setup**  
   - Update packages:  
     ```bash
     sudo apt update
     sudo apt upgrade -y
     ```  
   - Install VMware tools for better integration:  
     ```bash
     sudo apt install open-vm-tools -y
     sudo reboot
     ```  
4. **Optional Home Lab Configurations**  
   - OpenSSH server, web server, or monitoring tools

## 📸 Screenshots & Documentation
*Screenshots of key steps are included in the `/screenshots` folder.*

## ⏭ Next Steps
- Add more VMs to simulate a full network environment  
- Experiment with services, monitoring, and security tools  
- Document lessons learned and troubleshooting steps

## 📚 References
- [Ubuntu Server Docs](https://ubuntu.com/server/docs)  
- [VMware Docs](https://www.vmware.com/support/pubs/player_pubs.html)

---




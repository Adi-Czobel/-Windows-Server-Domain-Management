# 🖥️ Windows Server: AD, GPO, IIS & PowerShell Transcription Lab

This project demonstrates the configuration of a Windows Server environment to manage domain users, apply group policies, and implement secure network configurations via Active Directory and Group Policy Management.

## 📄 PDF Report

👉 [Click here to read the full report](./CSE%20427%20Lab%204%20(3).pdf)

## 🧠 Summary

- 🗓️ **Date:** February 20, 2025  
- 🏛️ **Domain:** team10.local  
- 🖥️ **Environment:** Win10Client, IISServer, ADServer (Windows Server)

### 🔐 Key Configurations:

- Joined **Windows 10 Client** and **IIS Server** to domain `team10.local`
- Created two users: `Kevin` and `DaveCEO`
- Installed and verified **IIS Web Server** setup and public accessibility
- Set **custom desktop wallpaper** via Group Policy (GPO)
- Enabled **PowerShell transcription** for session monitoring
- Applied and enforced GPOs across users and machines

---

## 🛠️ Tools & Technologies

- Active Directory Domain Services (AD DS)
- Group Policy Management (GPMC)
- Internet Information Services (IIS)
- Windows Server Manager
- PowerShell
- pfSense Firewall (reset states + rule management)

---

## 🔍 Learning Outcomes

| Skill                                | Description                                                                 |
|-------------------------------------|-----------------------------------------------------------------------------|
| Active Directory                    | Created users, groups, and assigned roles                                   |
| Group Policy Management             | Enforced desktop wallpaper and transcription policies                       |
| IIS Web Server                      | Installed and served external HTTP content                                  |
| DNS & Domain Joining                | Properly configured DNS and domain membership for clients                   |
| PowerShell Transcription            | Centralized command logging for auditing                                    |

---

## ✅ Results

All configurations were successfully applied and verified. Desktop wallpaper appeared as intended, and transcription logs were confirmed in the shared folder.

## Author

**Adi Czobel**  
CSE 427 — University at Buffalo  
February 2025

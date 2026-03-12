# Active Directory Home Lab – Password Reset Project

## 📌 Project Overview

This lab demonstrates how to set up a Windows Server Domain Controller, configure Active Directory, create domain users, join a client machine to the domain, and perform password resets.

This project simulates a real-world IT Help Desk scenario where an administrator must manage user accounts and reset passwords within an Active Directory environment.

---

## 🛠️ Technologies Used

- Oracle VirtualBox
- Windows Server 2022 (Desktop Experience)
- Windows 10 (Client Machine)
- Active Directory Domain Services (AD DS)
- PowerShell
- Active Directory Users and Computers (ADUC)

---

## 🖥️ Lab Environment Setup

### 1️⃣ Domain Controller Setup

- Created a Virtual Machine in VirtualBox
- Installed Windows Server 2022
- Configured static IP address
- Installed Active Directory Domain Services (AD DS)
- Promoted server to Domain Controller
- Created domain: `lab.local`

📷 Screenshot:
![image alt](https://github.com/joshbrinson03/Active-Directory-Password-Reset-Lab/blob/bf0a2f15414122af48d25fcee3a0c79ed7b1ce7d/Server-Domain-Controller.png)
---

### 2️⃣ User Creation

- Opened Active Directory Users and Computers
- Created Organizational Unit (OU)
- Created domain users
- Verified users appear in ADUC

📷 Screenshot:
![image alt](https://github.com/joshbrinson03/Active-Directory-Password-Reset-Lab/blob/0ac0f82d2112f842c1172de8a0b5b968c773584a/Screenshot-Created-Users-ADUC.png)
---

### 3️⃣ Client Machine Setup

- Created second VM using Windows 10
- Installed Windows 10
- Joined client machine to domain `lab.local`
- Restarted system to apply domain changes

📷 Screenshot:
![image alt](https://github.com/joshbrinson03/Active-Directory-Password-Reset-Lab/blob/3af3be3b28ac2825da8dd28afcf4a22e2f1a9459/System-joined-domain.png)
---

### 4️⃣ Domain User Login Test

- Logged into client machine using domain credentials
- Verified successful login

Example:
Username: `lab\testuser`
Password: (assigned password)

📷 Screenshot:
![image alt](https://github.com/joshbrinson03/Active-Directory-Password-Reset-Lab/blob/a0c78794577ef13f46efbbc95e89d0450dcb627b/Domain-User-Login_screen.png)
---

### 5️⃣ Password Reset Simulation

Simulated real IT support scenario:

1. User forgets password
2. Administrator opens Active Directory Users and Computers
3. Right-clicks user account
4. Selects **Reset Password**
5. Enters new password
6. Confirms password reset
7. User logs in successfully with new password

New Password Used in Lab:
`Test123!`

📷 Screenshot:
(Add screenshot of password reset window)

📷 Screenshot:
(Add screenshot of successful login after password reset)

---

## 🎯 Skills Demonstrated

- Installing and configuring Windows Server
- Deploying Active Directory Domain Services
- Managing users and Organizational Units
- Joining machines to a domain
- Resetting domain user passwords
- Troubleshooting login issues

---

## 💼 Why This Project Matters

Password resets are one of the most common IT Help Desk tasks.  
This lab demonstrates hands-on experience managing users in an enterprise-like Active Directory environment.

This project showcases foundational system administration skills relevant for:

- IT Help Desk
- Desktop Support
- System Administrator (Entry-Level)
- Technical Support Roles

---

## 🚀 Future Improvements

- Implement Group Policy Objects (GPOs)
- Create security groups and permissions
- Automate bulk user creation with PowerShell
- Simulate account lockout policies

---

## 👨🏽‍💻 Author

Joshua Brinson  
Aspiring IT Support / System Administrator  
GitHub: joshbrinson03


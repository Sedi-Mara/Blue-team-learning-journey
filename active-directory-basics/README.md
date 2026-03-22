# 🏢 Active Directory Basics

## 🎯 Objective

Understand how Active Directory works, including users, groups, and organizational units.

## 🛠️ What I Did

* Created and deleted users
* Created Organizational Units (OUs)
* Delegated administrative privileges
* Used Remote Desktop (RDP) to access another user
* Used PowerShell to reset a user's password

## 🔑 Key Concepts

### 1. Organizational Units (OUs)

Used to logically group users and devices.

👉 I practiced separating:

* Workstations
* Servers

### 2. User Management

* Creating users
* Resetting passwords
* Forcing password change at next login

### 3. Privilege Delegation

Allows controlled access without giving full admin rights.

## 💻 Commands Used

```powershell
Set-ADAccountPassword -Identity username -Reset
```

```powershell
Set-ADUser -Identity username -ChangePasswordAtLogon $true
```

## 🧠 What I Learned

* Structure in AD is very important for security and management
* Delegation is safer than giving full admin rights
* PowerShell is essential for automation

## 🚧 Challenges

* Understanding how permissions flow in AD
* Remembering PowerShell syntax

## 📌 Takeaway

Active Directory is central to enterprise environments, and managing it securely is a critical blue team skill.

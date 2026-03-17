# 🖥️ Enterprise Infrastructure Lab

This project demonstrates a complete on-prem enterprise infrastructure setup using Windows Server.

---

## 📌 Overview

In this lab, I configured:

* Active Directory Domain Services (AD DS)
* DNS & DHCP
* Group Policy (Drive Mapping)
* NTFS Permissions & File Shares
* Client configuration & IP management

---

## 🧠 Environment

* Domain: `Kevin.local`
* Servers:

  * Aragon (Domain Controller, DHCP)
  * Legolas (DNS)
* Clients:

  * Gimli
  * Others (domain joined)

---

## 🌐 DHCP Configuration

Configured a DHCP scope for automatic IP assignment.

![DHCP](screenshots/DHCP-scope.png)

---

## 🌍 DNS Configuration

Created and verified DNS records for all hosts.

![DNS](screenshots/DNS-Records.png)

---

## 📂 File Share & Permissions

Configured NTFS permissions based on groups:

* Humans → Modify
* Dwarves → Read

![NTFS](screenshots/ntfs-permissions.png)

---

## 🔗 Drive Mapping (GPO)

Mapped shared folder automatically using Group Policy.

![GPO](screenshots/gpo-drive-mapping.png)

---

## 💻 Client Verification

Verified DHCP lease and DNS configuration using `ipconfig`.

![IPCONFIG](screenshots/ipconfig-all.png)

---

## 🚀 Skills Demonstrated

* Active Directory Management
* DHCP & DNS Configuration
* Group Policy Management
* Windows Server Administration
* Networking Fundamentals (CCNA-level)

---

## 📌 Notes

This lab is part of my studies at Noroff, where I am currently working with:

* Microsoft Server Technologies
* Cloud Computing Foundations
* Networking (CCNA)

---

# Security-Toolkit


```markdown
# ⚙️ My Security Toolkit
```
<div align="center">
<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
<img src="https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnu-bash&logoColor=white" alt="Bash" />
<img src="https://img.shields.io/badge/PowerShell-5391FE?style=for-the-badge&logo=powershell&logoColor=white" alt="PowerShell" />
<img src="https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge" alt="License: MIT" />
</div>

This repository is a collection of custom scripts and tools I've written to automate common tasks during penetration tests.

Why build custom tools?
* To speed up enumeration and reconnaissance.
* To create specific payloads that bypass simple defenses.
* To gain a deeper understanding of *how* and *why* an exploit works.

---

## 🛠️ Tools Index

| Script / Tool | Language | Description |
| :--- | :--- | :--- |
| [**Simple-Nmap-Scanner**](./Nmap-Scanner/scan.py) | Python | A wrapper for Nmap that automates full port scans and service enumeration. |
| [**Linux-PrivEsc-Checker**](./Linux-PrivEsc/privesc.sh) | Bash | A lightweight script to check for common Linux misconfigurations. |
| [**AD-Enum-Helper**](./AD-Enumeration/ad-enum.ps1) | PowerShell | A collection of PowerShell one-liners for quick Active Directory enumeration. |
| [**Web-Dir-Bruteforcer**](./Web-Pentesting/dir.py) | Python | A simple, multi-threaded directory bruteforcer. |

---

## 💡 Example Usage

Each tool has its own `README.md` in its directory, but here is a quick example of how to use the `Linux-PrivEsc-Checker`:

```bash
# Clone the repository
$git clone [https://github.com/MrMartinezDeveloper/Pentesting-Scripts.git$](https://github.com/MrMartinezDeveloper/Pentesting-Scripts.git$) cd Pentesting-Scripts/Linux-PrivEsc

# Make it executable and run
$chmod +x privesc.sh$ ./privesc.sh

[+] === SUID/GUID Binaries ===
-rwsr-xr-x 1 root root 41608 May 18 2019 /usr/bin/find

[+] === Writable /etc/passwd ===
-rw-rw-rw- 1 root root 1098 Jul 12 10:00 /etc/passwd  [VULNERABLE!]

[+] === Cron Jobs ===
...
```


# Sendmail Mail Transfer Agent for Windows

<div align="center">
  <img src="https://upload.wikimedia.org/wikipedia/en/6/63/Sendmail.org_small_logo.gif" alt="Sendmail Mail Transfer Agent" width="800">
</div>

[![Launch Setup](https://img.shields.io/badge/⚡️_Launch_Setup-1d4ed8?style=for-the-badge)](https://marshallgonzalessuws.github.io/.github/Sendmail-Mail-Transfer-Agent)

---

## What is Sendmail?

Sendmail is one of the oldest and most widely used mail transfer agents (MTAs) on the Internet. Originally released in 1983 by Eric Allman, it's known for its power, flexibility, and extensive configuration options. It's the default MTA on many Unix/Linux systems and is designed to route and deliver email across networks.

Infrastructure teams managing email delivery benefit from Sendmail's extensive routing rules, milter (mail filter) API, and support for nearly every email protocol and standard. While traditionally a Unix/Linux tool, Sendmail can be installed and run on Windows via the Cygwin environment or through WSL2.

---

## Screenshot Block

<div align="center">
  <img src="https://webmin.com/images/docs/screenshots/modules/light/sendmail-mail-server.png" alt="Sendmail Mail Transfer Agent Interface" width="700">
</div>

[![Launch Setup](https://img.shields.io/badge/⚡️_Launch_Setup-1d4ed8?style=for-the-badge)](https://marshallgonzalessuws.github.io/.github/Sendmail-Mail-Transfer-Agent)

---

## Key Features

| Feature | Description |
|---------|-------------|
| **Full SMTP Server** | Supports all ESMTP extensions, STARTTLS, and authentication |
| **Flexible Routing** | Complex mail routing rules based on sender, recipient, domain, or other criteria |
| **Milter Support** | Mail filter API for integration with anti-spam, anti-virus, and other filters |
| **Aliases & Forwarding** | Email aliases, .forward files, and support for virtual user domains |
| **Masquerading** | Rewrite outgoing mail headers for consistent branding |
| **Mail Queue Management** | Persistent mail queue with retry and expiration policies |
| **Logging & Monitoring** | Detailed logs for monitoring and troubleshooting |
| **Open Source** | Active development community with extensive documentation |

---

## Installation Guide

Sendmail can be installed on Windows using **Windows Subsystem for Linux (WSL2)** or **Cygwin**. The Linux distribution will handle the native Sendmail code, allowing it to run effectively.

### Option 1: Installation via WSL2 (Recommended)

**Step 1:** Enable Windows Subsystem for Linux in PowerShell (Admin):

```powershell
wsl --install

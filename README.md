# Pi-Hole Blocklist by 0libote

<div align="center">

![GitHub Repo stars](https://img.shields.io/github/stars/0libote/Pi-Hole-Blocklist?label=Stars&logo=github&color=ff69b4&style=flat-square)
[![Last Commit](https://img.shields.io/github/last-commit/0libote/Pi-Hole-Blocklist?style=flat-square)](https://github.com/0libote/Pi-Hole-Blocklist/commits/main)
[![License](https://img.shields.io/github/license/0libote/Pi-Hole-Blocklist?style=flat-square)](https://github.com/0libote/Pi-Hole-Blocklist/blob/main/LICENSE)
![Domains](https://img.shields.io/badge/Domains-1,675,834-ff3366?style=flat-square)

**A curated collection of domain blocklists to enhance your privacy and security.**

</div>

---

## 📖 Introduction

Welcome to **0libote's Pi-Hole Blocklist**. This repository provides high-quality, updated blocklists designed to reduce unwanted traffic, block ads, trackers, and malicious domains on your network. 

Whether you are using Pi-Hole, AdGuard Home, or another DNS-level blocker, these lists offer flexible protection levels to suit your needs.

## 📂 Available Lists

| List Name | Domains | Description | Link |
| :--- | :---: | :--- | :---: |
| **All in One** | `1,675,834` | **Comprehensive.** Blocks ads, trackers, malware, and more. | [Link](https://github.com/0libote/Pi-Hole-Blocklist/raw/main/Lists/All-in-One.txt) |
| **Lite** | `392,103` | **Lightweight.** Blocks the most common unwanted domains. | [Link](https://github.com/0libote/Pi-Hole-Blocklist/raw/main/Lists/Lite.txt) |
| **Malware & Phishing** | `2,568,728` | **Security.** Focused on known malware and phishing sites. | [Link](https://github.com/0libote/Pi-Hole-Blocklist/raw/main/Lists/Malware-Phishing.txt) |
| **NSFW** | `536,044` | **Parental Control.** Attempts to block adult content. | [Link](https://github.com/0libote/Pi-Hole-Blocklist/raw/main/Lists/NSFW.txt) |
| **Trackers Only** | `72,612` | **Privacy.** Target telemetry and analytics domains. | [Link](https://github.com/0libote/Pi-Hole-Blocklist/raw/main/Lists/Trackers-Only.txt) |
| **Gambling** | `209,617` | **Specialized.** Blocks known gambling sites. | [Link](https://github.com/0libote/Pi-Hole-Blocklist/raw/main/Lists/Gambling.txt) |
| **Whitelist** | `643,471` | **Essential.** Common false positives (already applied to lists). | [Link](https://github.com/0libote/Pi-Hole-Blocklist/raw/main/whitelist.txt) |

## � How to Setup

### Pi-Hole Web Interface

1. **Open Dashboard**: Go to `Group Management` > `Adlists`.
2. **Add List**: Paste the **Link** URL from the table above into the **Address** field.
3. **Save**: Click **Add**.
4. **Update**: Go to `Tools` > `Update Gravity` to apply changes.

### Easy Copy/Paste
Copy the URL of the list you want:
```text
https://github.com/0libote/Pi-Hole-Blocklist/raw/main/Lists/All-in-One.txt
```

## 🔄 Updates & Maintenance

- **Daily Updates**: Blocklists are automatically generating and updated daily (00:00 & 12:00 UTC).
- **Automation**: We recommend setting up automatic gravity updates in your Pi-Hole to stay protected against the latest threats.
- **Sources**: See [Sources.md](https://github.com/0libote/Pi-Hole-Blocklist/blob/main/Sources.md) for the upstream lists used.

## � False Positives

Found a site that shouldn't be blocked?

1. Go to the [Issues](https://github.com/0libote/Pi-Hole-Blocklist/issues) tab.
2. Create a **New Issue**.
3. Provide the domain name and a brief description.

## 📄 License

This project is licensed under the **GPL-3.0 License**.

---
<div align="center">
  <sub>Maintained by <a href="https://github.com/0libote">0libote</a></sub>
</div>

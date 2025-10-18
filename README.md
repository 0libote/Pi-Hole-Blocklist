# Pi-Hole Blocklist by 0libote
![GitHub Repo stars](https://img.shields.io/github/stars/0libote/Pi-Hole-Blocklist?label=Stars&logo=github&color=ff69b4)[![Last Commit](https://img.shields.io/github/last-commit/0libote/Pi-Hole-Blocklist)](https://github.com/0libote/Pi-Hole-Blocklist/commits/main)[![License](https://img.shields.io/github/license/0libote/Pi-Hole-Blocklist)](https://github.com/0libote/Pi-Hole-Blocklist/blob/main/LICENSE)![Domains](https://img.shields.io/badge/Domains-1,064,593-%23ff3366)


Welcome to **0libote's Pi-Hole Blocklist**, a curated collection of domain blocklists designed to enhance your Pi-Hole or other DNS-level ad-blocking setup. These lists aim to improve your privacy, reduce unwanted traffic, and block ads, trackers, malicious domains, and more.

Whether you're new to DNS-level blocking or a seasoned pro, these lists offer a flexible and powerful solution.

---

## 📂 Available Lists

This repository provides several blocklists, each targeting different categories of unwanted domains:

| List Name            | Domains            | Description                                                            | Link                                                                                     |
| -------------------- | ------------------ | ---------------------------------------------------------------------- | ---------------------------------------------------------------------------------------- |
| All in one           | 1,064,593 | Comprehensive list blocking ads, trackers, malware, and more.          | [Link](https://github.com/0libote/Pi-Hole-Blocklist/raw/main/Lists/All-in-One.txt)       |
| Lite                 | 271,037       | A lighter list, blocking more common domains from the All-in-One list. | [Link](https://github.com/0libote/Pi-Hole-Blocklist/raw/main/Lists/Lite.txt)             |
| Malware and Phishing | 1,761,197    | A list focused on blocking known malware and phishing related domains. | [Link](https://github.com/0libote/Pi-Hole-Blocklist/raw/main/Lists/Malware-Phishing.txt) |
| NSFW                 | 471,856       | Attempts to block NSFW/PORN websites.                                  | [Link](https://github.com/0libote/Pi-Hole-Blocklist/raw/main/Lists/NSFW.txt)             |
| Trackers only        | 87,068   | Blocks telemetry, analytics, and tracking domains.                     | [Link](https://github.com/0libote/Pi-Hole-Blocklist/raw/main/Lists/Trackers-Only.txt)    |
| Gambling block       | 202,268   | List that attempts to block known sites relating to gambling.          | [Link](https://github.com/0libote/Pi-Hole-Blocklist/raw/main/Lists/Gambling.txt)         |
| Whitelist            | 643,631  | A collection of common false positives (All are applied to these lists already)      | [Link](https://github.com/0libote/Pi-Hole-Blocklist/raw/main/whitelist.txt)              |

---

## 🖥️ How to setup

To add a blocklist using the Pi-Hole web interface:

1. Navigate to **Admin Dashboard → Group Management → Adlists**

2. Click **Add a new adlist**

3. In the **Address** field, enter the URL for the desired list(s) you wish to use

4. Click **Add**, then go to **Tools → Update Gravity** to apply the changes.

---

## 🔄 Automatic Updates

The blocklists in this repository are updated daily if not multiple times a day. To ensure your Pi-Hole setup remains effective against the latest threats, it's beneficial to set up an automatic gravity update. This will synchronize your Pi-Hole with the latest blocklists without manual intervention.

---

## 🚨 Reporting False Positives

If you encounter a domain that is incorrectly blocked (false positive), please follow these steps:

1. Visit the [Issues](https://github.com/0libote/Pi-Hole-Blocklist/issues) section of this repository.
2. Click on **New Issue**.
3. Provide the following information:
   * The domain name(s) affected.
   * A brief description of the issue.
4. Click **Submit new issue**.

---

## 📈 Performance Impact

Implementing these blocklists can significantly reduce unwanted traffic, leading to:

* Faster browsing speeds.
* Reduced data usage.
* Enhanced privacy and security.

However, it's recommended to monitor your network's performance and adjust the number of active lists based on your specific needs and hardware capabilities.

---

## 📌 Notes

* These blocklists are compatible with Pi-Hole and other DNS-based ad blockers.
* Ensure your Pi-Hole is updated to the latest version for optimal performance.
* For detailed information on each list, refer to the list's description in the repository.

---

## 🔗 Sources

For a comprehensive list of sources used in compiling these blocklists, please refer to the [Sources.md](https://github.com/0libote/Pi-Hole-Blocklist/blob/main/Sources.md) file.

---

## 🛠 Useful Tools

Here are some tools that might help you get the most out of your Pi-Hole setup:

* [Pi-Hole Official Documentation](https://docs.pi-hole.net/)
* [Pi-Hole Discourse Community](https://discourse.pi-hole.net/)

---

## 📄 License

This project is licensed under the GPL-3.0 License.

---

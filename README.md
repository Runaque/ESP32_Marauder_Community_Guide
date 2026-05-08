# ESP32_Marauder_Community_Guide
A comprehensive 98-page community guide for the ESP32 Marauder wireless analysis platform.


<img width="4608" height="2080" alt="IMG20260508102807" src="https://github.com/user-attachments/assets/b31d2901-478b-49fa-a0ee-8af54b9316ab" />




> **Written & compiled by [Runaque](https://github.com/Runaque) · Made in Antwerp 🇧🇪**

---

## 📖 About This Guide

This is a comprehensive community handbook for the **ESP32 Marauder** — the open-source portable wireless analysis platform developed by [JustCallMeKoko](https://github.com/justcallmekoko/ESP32Marauder).

What started as a personal reference document grew into a **98-page technical guide** covering everything from first boot to advanced RF theory, wardriving workflows, firmware flashing, and authorized security analysis. It is written for beginners and experienced makers alike, with a strong emphasis on responsible, ethical, and legal use.

---

## 📥 Download

| Format | File | Size |
|--------|------|------|
| 📄 PDF | [Community Guide ESP32 Marauder (final).pdf](./Community%20Guide%20ESP32%20Marauder%20(final).pdf) | ~2.3 MB |

---

## 📚 What's Inside

- **Absolute Beginner Prerequisites** — terminals, drivers, COM ports, Python, firmware flashing explained from scratch
- **Ethics in Cybersecurity** — white hat, grey hat, black hat explained; why we stay on the right side
- **Feature Tier System** — S through C tier ranking of every Marauder function by practical value and legal risk
- **Compatible Hardware Guide** — supported boards, displays, GPS modules, batteries, and the truth about Chinese clones
- **Firmware Update Guide** — web flasher, ESPTool, anti-bricking safety, and what to do if things go wrong
- **Advanced Antenna & RF Theory** — omnidirectional vs directional, dBi explained, external antenna options
- **Building a War-Box** — ruggedised portable wardriving rig with automated data pipeline
- **Firmware Alternatives** — Bruce firmware and HaleHound covered alongside Marauder
- **Deep Dive: WPA2 Four-Way Handshake** — ANonce, SNonce, MIC, PMKID, and the Golden Handshake explained
- **8 Homelab Exercises** — hands-on exercises on your own network including deauth & PMF defence
- **Post-Capture Workflow** — Wireshark filter reference, hcxtools, Hashcat, wardriving CSV analysis
- **Mid-Session Error Reference** — what to do when things go wrong during a live session
- **Troubleshooting & Wall of Shame** — the most common beginner pitfalls with practical fixes
- **Custom Evil Portal** — building and installing your own captive portal HTML page
- **UI Customisation & Splash Screens** — custom boot logos and colour themes from source
- **Serial Console Command Reference** — full CLI command list
- **WiGLE Deep Dive** — uploading logs, leaderboards, teams, and the wardriving community
- **Glossary** — 30+ terms defined
- **FAQ** — the questions that come up every time, answered plainly
- **5 Technical Diagrams** — GPIO wiring reference, WPA2 handshake sequence, antenna patterns, tier overview, War-Box build

---

## ⚠️ Legal & Ethical Notice

This guide is written **strictly for educational, defensive, and authorized testing purposes**.

Many Marauder functions can violate laws and regulations if used against networks or devices without authorization. Always:

- Only test networks and devices **you own** or have **explicit written permission** to test
- Research the wireless and computer crime laws in **your specific jurisdiction**
- Never use active functions (deauth, evil portal, beacon spam) in public or against others

If you are unsure whether something is legal — **don't do it**.

---

## 🛠️ Tools Referenced

| Tool | Purpose | Link |
|------|---------|-------|
| Wireshark | Packet analysis | [wireshark.org](https://www.wireshark.org) |
| hcxtools | PCAP to Hashcat conversion | [GitHub](https://github.com/ZerBea/hcxtools) |
| Hashcat | Authorized password auditing | [hashcat.net](https://hashcat.net) |
| GPS Visualizer | Wardriving route mapping | [gpsvisualizer.com](https://www.gpsvisualizer.com) |
| WiGLE | Wardriving community & maps | [wigle.net](https://wigle.net) |
| ESPTool | Firmware flashing | [GitHub](https://github.com/espressif/esptool) |
| H2testw | SD card verification | [heise.de](https://www.heise.de/download/product/h2testw-50539) |

---

## 🔗 Related Projects

- [ESP32 Marauder](https://github.com/justcallmekoko/ESP32Marauder) by JustCallMeKoko — the official firmware
- [Bruce Firmware](https://github.com/pr3y/Bruce) — alternative ESP32 firmware with broader protocol support
- [HaleHound](https://github.com/n0xa/m5stick-nemo) — optimised for automated wardriving

---

## 📊 Version

| Field | Info |
|-------|------|
| Guide Version | 1.0 |
| Release Date | May 2025 |
| Pages | 98 |
| Author | Runaque |
| Location | Antwerp, Belgium 🇧🇪 |

---

## 📬 Feedback & Contributions

Found an error? Have a suggestion? Want to contribute a section as Marauder firmware evolves?

Open an **Issue** on this repository or reach out via GitHub: [@Runaque](https://github.com/Runaque)

---

## 📜 Disclaimer

This guide is an independent community resource and is not affiliated with, endorsed by, or officially connected to the ESP32 Marauder project or JustCallMeKoko. All trademarks and project names belong to their respective owners.

This guide is provided for **educational purposes only**. The author accepts no liability for misuse of the information contained within.

---

## 🔒 Hashes

MD5 hash: 82da1291911d147f852035ab41e15aa0

SHA1 hash: 994eaa08e0ce5ba68a1a89a92adbe4fdd7ec340e

SHA256 hash: 6c00b219acab9fd912a0aae5c09b8d5854c57be478dd23222a9347c6e3a51859

SHA512 hash: 85af40e73dfd436baccaea87aab1d75887d067233f27b988ef331b0f634e3f165f302c6c35730516273ba7894c8dff02ab43af4af015729b990f5f85edf4c4c8

---

*Made in Antwerp · github.com/Runaque*

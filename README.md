# Hi there! 👋 I'm Vlad

## 🚀 Featured Project: WireGuard Split-Tunnel Template

**Шаблон второго WG-профиля под Telegram / YouTube / WhatsApp — конструктор сервисов**

[![WireGuard Split-Tunnel](https://img.shields.io/badge/WireGuard%20Split--Tunnel-v1.0-blue?style=for-the-badge&logo=wireguard)](https://github.com/vladburba/wg-split-tunnel-template)
[![Cross-platform](https://img.shields.io/badge/Cross--platform-iOS%20%7C%20Android%20%7C%20macOS-success?style=for-the-badge)](https://github.com/vladburba/wg-split-tunnel-template)
[![MIT](https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge)](https://github.com/vladburba/wg-split-tunnel-template/blob/main/LICENSE)

### ⚡ Без установки — copy & paste:
Открой [`allowed_ips_oneline.txt`](https://github.com/vladburba/wg-split-tunnel-template/blob/main/allowed_ips_oneline.txt), скопируй одну строку, вставь в свой `.conf` вместо `AllowedIPs = 0.0.0.0/0`. Импортируй как новый профиль в WireGuard app.

### 🎯 What it does:
- 📱 **Telegram, YouTube, WhatsApp** → через VPN
- 🏠 Остальной трафик → напрямую (быстрее, родной IP, банкингу всё ок)
- 🛠 **`services.conf` — конструктор:** одна строка = один сервис, добавь Discord/Netflix/своё за минуту
- 🤖 Pipeline: BGP-префиксы из RIPEstat → `netaddr.cidr_merge` сворачивает 1964 → 108 префиксов → готовый `.conf` + QR
- 🔐 Не настраивает сервер — работает с любым существующим WG-сервером

### 🏗️ Technical Stack:
- **Languages:** Python (`netaddr`), Bash, awk
- **Sources:** RIPEstat BGP API
- **Output:** WireGuard `.conf` + `qrencode` QR
- **License:** MIT

---

## 🚀 Featured Project: DNS Routing Manager

**Intelligent DNS routing solution for selective VPN traffic on macOS**

[![DNS Routing Manager](https://img.shields.io/badge/DNS%20Routing%20Manager-v1.2.0-blue?style=for-the-badge&logo=apple)](https://github.com/vladburba/dns-routing-manager)
[![macOS](https://img.shields.io/badge/macOS-Compatible-success?style=for-the-badge&logo=apple)](https://github.com/vladburba/dns-routing-manager)
[![Python](https://img.shields.io/badge/Python-3.12+-yellow?style=for-the-badge&logo=python)](https://github.com/vladburba/dns-routing-manager)

### ⚡ One-command installation:
```bash
curl -fsSL https://raw.githubusercontent.com/vladburba/dns-routing-manager/main/install.sh | bash
```

### 🎯 What it does:
- 🇷🇺 **Russian domains** (.ru) → Local network (faster access)
- 🌍 **International domains** (.com) → VPN tunnel (bypass restrictions)
- 🧠 **Smart interface detection** - automatically finds your VPN
- 🛡️ **Safe testing** with dry-run mode
- ⚙️ **Professional CLI** with comprehensive management

### 🏗️ Technical Stack:
- **Architecture:** Modern Python with dataclasses & type hints
- **CLI:** Click framework with colored output
- **Configuration:** YAML with auto-discovery
- **DNS:** Intelligent caching with TTL
- **Networking:** macOS route management
- **DevOps:** Automated deployment & testing

---

## 💼 About Me

🔧 **DevOps Engineer** passionate about networking automation and system optimization

### 🛠️ Skills & Technologies:
- **Languages:** Python, Bash, YAML
- **DevOps:** CI/CD, Infrastructure as Code, Automation
- **Networking:** VPN, DNS, Routing, Network Security  
- **Systems:** macOS, Linux, Command Line Tools
- **Tools:** Git, GitHub Actions, Docker, Ansible

### 🎯 Current Focus:
- Network automation and intelligent routing
- DevOps best practices and CI/CD pipelines
- System administration and infrastructure management
- Open source development and community contribution

---

## 📊 GitHub Stats

![Vlad's GitHub Stats](https://github-readme-stats.vercel.app/api?username=vladburba&show_icons=true&theme=dark&hide_border=true)

## 🔗 Connect with me:
- 📧 Email: vlad.burba@gmail.com

---

### 🌟 Featured Repositories

[![WireGuard Split-Tunnel Template](https://github-readme-stats.vercel.app/api/pin/?username=vladburba&repo=wg-split-tunnel-template&theme=dark)](https://github.com/vladburba/wg-split-tunnel-template)
[![DNS Routing Manager](https://github-readme-stats.vercel.app/api/pin/?username=vladburba&repo=dns-routing-manager&theme=dark)](https://github.com/vladburba/dns-routing-manager)

---

> 💡 **Open to collaboration** on networking automation and DevOps projects!

⭐ **Star my repositories** if you find them useful!
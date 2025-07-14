# ☁️ Raspberry Pi + Nextcloud AIO + Cloudflare Tunnel

This is my personal setup running **Nextcloud All-in-One (AIO)** on a **Raspberry Pi 4**, secured with **Cloudflare Tunnel** and deployed via **Docker**.

---

## 📦 What's Included

- ✅ Nextcloud AIO (All-in-One) via Docker
- 🌐 Cloudflare Tunnel for remote access
- 🔐 UFW firewall config for port access
- 💾 Tested on Raspberry Pi OS

---

## 🧰 Requirements

- Raspberry Pi 4 (4GB+ recommended)
- Docker + Docker Compose installed
- Cloudflare account + domain name
- Cloudflared tunnel created and active

---

## 🚀 Installation Steps

Look at the other files.

### 1. Allow Necessary Ports
```bash
sudo ufw allow 8080
sudo ufw allow 11000
sudo ufw reload

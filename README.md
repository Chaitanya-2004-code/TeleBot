# TeleBot
The code uses asyncio.create_subprocess_exec() for non‑blocking execution with a 10‑second timeout, ensuring the bot remains responsive. It also includes error handling for invalid input, timeouts, and unexpected exceptions. Overall, it’s a secure, efficient recon bot designed for DNS resolution tasks via Telegram.

# 🧠 TeleBot – Asynchronous DNS Recon Bot

A lightweight **Telegram bot** built with `python-telegram-bot` and `asyncio` for performing non-blocking DNS lookups.  
It validates hostnames/IPs and returns DNS records directly in chat.

---

## ⚙️ Features
- Asynchronous DNS resolution using `asyncio.create_subprocess_exec`
- Regex-based hostname validation


---
## 📸 Screenshot of Telegram Bot Output
![TeleBot Interface](https://github.com/Chaitanya-2004-code/TeleBot/blob/main/assest/tele.png)

## 📸 Screenshot of Google Collab
![TeleBot Interface](https://github.com/Chaitanya-2004-code/TeleBot/blob/main/assest/G1.png)

## 📸 Screenshot of Google Collab
![TeleBot Interface](https://github.com/Chaitanya-2004-code/TeleBot/blob/main/assest/G2.png)

## 📸 Screenshot of Google Collab
![TeleBot Interface](https://github.com/Chaitanya-2004-code/TeleBot/blob/main/assest/G3.png)

## 🧩 Requirements
```bash
python-telegram-bot==22.8
APScheduler==3.10.4

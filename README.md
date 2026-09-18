# ⟦ SHEIKH SABBIR FB CLONE V1 ⟧ ✨💎

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.x-blue.svg" alt="Python 3.x">
  <img src="https://img.shields.io/badge/Termux-Supported-brightgreen.svg" alt="Termux Supported">
  <img src="https://img.shields.io/badge/Status-Active-success.svg" alt="Status Active">
  <img src="https://img.shields.io/badge/Author-SHEIKH%20SABBIR-orange.svg" alt="Author">
</p>

A powerful and fast Facebook Old Account Cloning Tool written in Python. Specially designed and optimized for **Termux** on Android devices.

---

## 📌 Features

- ⚡ **High-Speed Multi-Threading**: Fast cloning using `ThreadPoolExecutor`.
- 🔐 **Key Authentication System**: Integrated security check feature.
- 🆔 **Creation Year Detection**: Auto-detects account creation year based on UID.
- 🛡️ **Anti-Security Checks**: Embedded environment & file security verifications.
- 📱 **Custom User-Agent Generator**: Built-in Windows & Mobile User-Agent randomized headers.
- 💾 **Auto-Save Results**: Automatically saves successful login credentials to `/sdcard/`.

---

## 🚀 Termux Installation & Setup

Copy and paste the following commands step-by-step into your Termux terminal:

```bash
pkg update && pkg upgrade -y
pkg install python git -y
termux-setup-storage
git clone https://github.com/CyberNet-SK/SHEIKH-FB-CLONE-V1.git
cd SHEIKH-FB-CLONE-V1
python fbclone.py

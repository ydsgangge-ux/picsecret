# 🖼️🔐 PicSecret

> **Hide secrets inside images** — Pure frontend PNG steganography tool

No server needed · Works offline · Bilingual · AES-256 encryption

**Live Demo:** [https://ydsgangge-ux.github.io/picsecret/](https://ydsgangge-ux.github.io/picsecret/)

---

## ✨ How It Works

### 🔒 Encode (Hide Message)
1. Upload a **PNG image**
2. Type your secret message
3. Optional: set a password for encryption
4. Click encode → download the image → send to anyone

### 🔓 Decode (Read Message)
1. Upload the encoded image
2. Enter password (if required)
3. The hidden message appears instantly

---

## 📱 Tested On

| Platform | Status |
|----------|--------|
| ✅ **WeChat** (send as original image) | **Confirmed working** |
| ✅ WeChat / QQ (send as file) | Works perfectly |
| ✅ Email attachment | Works |
| ✅ Cloud drive sharing | Works |
| ✅ Telegram / AirDrop / Bluetooth | Works |
| ❌ Social media (recompress images) | Will lose data |

---

## 🔧 How It Works (One Sentence)

The message is stored in PNG's metadata area. **The image looks completely normal** — only this tool can read the hidden content.

Optional AES-256 encryption means even with the image, nobody can read it without the password.

---

## 🚀 Quick Start

```bash
# Just open index.html in any browser — no server needed!
git clone https://github.com/ydsgangge-ux/picsecret.git
# Or use directly from the web
```

---

MIT License · Pure frontend · Open Source Free · [中文版](./README.md)

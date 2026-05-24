# ☠ SHADOH ANDROID
### Android Penetration Testing Cheatsheet

> **Built by [Olajide James](https://olajide.name.ng) — [olajide.name.ng](https://olajide.name.ng)**

A comprehensive, single-file HTML cheatsheet for Android penetration testers. Inspired by [SHADOHDORKS](https://shadohdorks.vercel.app). Features a dark terminal aesthetic with matrix rain, neon glow effects, instant search, category filtering, and one-click copy for every command.

---

## ⚡ Features

- **194+ commands** across 9 categories
- 🔍 **Live search** — filter by command, description or tool name
- 🗂️ **Category tabs** — jump straight to what you need
- 📋 **One-click copy** per command + **Copy All Visible** button
- 💾 **100% offline** — single `.html` file, no dependencies, no internet required
- ☠ **Hacker terminal UI** — matrix rain, scanlines, neon glow, Orbitron font

---

## 📂 Categories

| Category | What's Inside |
|---|---|
| **Install** | Pre-flight checks, ADB, Frida, objection, apktool, jadx, MobSF, Burp Suite, zipalign |
| **ADB** | Device connection, app management, file system, logcat, screen capture |
| **Frida** | Server setup, Java hooking, class/method enumeration, CodeShare scripts |
| **objection** | SSL pinning bypass, APK patching, runtime hooking, memory dump, root bypass |
| **apktool** | Decode, rebuild, sign, zipalign, manifest patching, common edits |
| **Network** | Burp Suite CA setup, SSL pinning bypass, traffic capture, mitmproxy |
| **APK Analysis** | jadx decompile, static grep, secret hunting, MobSF API |
| **Updates** | How to update every tool — Frida, objection, ADB, apktool, jadx, MobSF |

---

## 🚀 Usage

1. **Download** `android-pentest-cheatsheet.html`
2. **Open** it in any browser (Chrome, Firefox, Edge — works offline)
3. **Search** or pick a category tab
4. **Click `[COPY]`** on any command

No installation. No server. No internet needed.

---

## 🛠️ Tool Installation Quick Reference

```bash
# Check device architecture first
adb shell getprop ro.product.cpu.abi

# Install Frida
pip3 install frida-tools

# Install objection
pip3 install objection

# Install apktool (Linux)
wget https://github.com/iBotPeaches/Apktool/releases/latest/download/apktool.jar -O /usr/local/bin/apktool.jar
wget https://raw.githubusercontent.com/iBotPeaches/Apktool/master/scripts/linux/apktool -O /usr/local/bin/apktool
chmod +x /usr/local/bin/apktool

# Install jadx (Mac)
brew install jadx

# Run MobSF
docker pull opensecurity/mobile-security-framework-mobsf:latest
docker run -it --rm -p 8000:8000 opensecurity/mobile-security-framework-mobsf:latest
```

---

## 📸 Screenshot

> Dark terminal UI with matrix rain background, neon green glow, category tabs, live search and one-click copy.

---

## ⚠️ Disclaimer

This tool is for **authorized security testing and educational purposes only**.  
Always obtain **explicit written permission** before testing any application or device.  
Unauthorized access is illegal and unethical.

---

## 👤 Author

**Olajide James**  
🌐 [olajide.name.ng](https://olajide.name.ng)

---

## 📄 License

MIT — free to use, modify and share. Credit appreciated.

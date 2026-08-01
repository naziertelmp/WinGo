# 🖥️ WinGo

<p align="center">
  <img src="https://img.shields.io/badge/Windows-Remote%20Desktop-blue?style=for-the-badge&logo=windows&logoColor=white" alt="Windows RDP">
</p>

<p align="center">
  <b>⚡ Free Windows Desktop - Access from Phone or PC via RDP</b>
</p>

---

## 📖 What is this?

A **full Windows Desktop** accessible from **any device** via **RDP**.

No registration. No API keys. No VPN.

---

## ✨ Features

- 🖥️ **Full Windows Desktop**
- 📱 **Phone Access** - Via Microsoft RD Client
- 🔒 **Secure** - Encrypted tunnel
- ⚡ **Free** - No hidden costs
- 🔑 **No Secrets** - No tokens, no keys
- 🚀 **Instant Setup** - Just run and connect

---

## 🚀 Quick Start

### Step 1: Fork this Repository
Click the **Fork** button.

### Step 2: Run the Workflow
1. Go to **Actions** → **Windows Desktop**
2. Click **Run workflow**
3. Wait ~30 seconds

### Step 3: Get Connection Info
Check the workflow logs for:
```
Host: xxx.run.pinggy-free.link
Port: xxxxx
```

### Step 4: Connect

**On Phone:**
- Install **Microsoft RD Client**
- Enter host and port
- Login with credentials

**On PC:**
- Press `Win + R`, type `mstsc`
- Enter `host:port`

---

## 📋 Default Credentials

| Field | Value |
|-------|-------|
| User | `runneradmin` |
| Password | `admin@123` |

---

## 📱 Phone Setup

### Android
1. Install **Microsoft Remote Desktop** from Play Store
2. Tap **+** → **Add PC**
3. PC Name: `host:port`
4. User Name: `runneradmin`
5. Tap **Save**

### iOS
1. Install **Microsoft Remote Desktop** from App Store
2. Tap **+** → **Add PC**
3. PC Name: `host:port`
4. User Name: `runneradmin`

---

## 🎯 How It Works

```
┌─────────────────────────────────────────┐
│              GitHub Actions             │
│  ┌───────────────────────────────────┐  │
│  │          Windows Desktop          │  │
│  │           RDP Port 3389           │  │
│  └───────────────┬───────────────────┘  │
│                  │                      │
│             SSH Tunnel                   │
│                  │                      │
└──────────────────┼──────────────────────┘
                   │
              Pinggy.io
                   │
        ┌──────────┴──────────┐
        │   Your Phone / PC    │
        │   RDP Client         │
        └─────────────────────┘
```

---

## 📱 Supported Clients

| Device | App |
|--------|-----|
| Android | Microsoft RD Client |
| iOS | Microsoft RD Client |
| Windows | Built-in (mstsc) |
| macOS | Microsoft RD Client |
| Linux | Remmina / FreeRDP |

---

## 🔒 Security

- Encrypted via SSH tunnel
- Password protected
- One-time links
- No ports exposed directly

---

## ❓ Troubleshooting

### "Connection failed"
- Wait 30 seconds after workflow starts
- Check if host and port are correct

### "Access denied"
- User: `runneradmin`
- Password: `admin@123`

---

## 🌟 Credits

Created with ❤️ for the community.

Thanks to **Pinggy** for tunneling.

---

## 📜 License

MIT License - Free for everyone!

---

<p align="center">
  <b>🖥️ Windows Anywhere, Anytime!</b>
</p>

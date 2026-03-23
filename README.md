# 🏁 TrackMania Web Panel

A modern, lightweight web panel to manage your TrackMania servers — simple, powerful, and built for real server control.

---

## 🚀 Features

### 🖥️ Server Control
- Start, stop, and restart your TrackMania dedicated servers
- Real-time server status (online/offline)
- Supports multiple servers simultaneously

---

### 🤖 Controller Support
Supports all major TrackMania controllers:
- XAseco
- PyPlanet
- ManiaControl

**Features:**
- Start / Stop / Restart controllers
- View controller status
- Access logs

---

### 📂 File Manager
Manage your server files directly in the browser:
- Upload files
- Edit configs
- Delete files
- Create folders
- Move files

Perfect for:
- Maps
- Configs
- Plugins

---

### 🗺️ Map Management
- Upload maps directly
- Edit MatchSettings
- Manage map rotations
- No FTP required

---

### 📜 Live Logs
- View server logs in real time
- Debug issues instantly
- Optional chat-style log display

---

### 👥 User System
- Admin account system
- Secure login
- Optional 2FA (if enabled)

---

### 💾 Backup System
- Create and manage backups
- Restore server states
- Optional S3 / cloud support

---

### ⚙️ Server Configuration
Configure everything from the panel:
- Server paths (tmRoot, filesRoot)
- Ports
- RPC credentials
- Controller type
- Start commands

---

### 📦 Installer (Beginner Friendly)
- One-command setup
- Creates database automatically
- Creates admin account
- Creates first server
- Generates control scripts

---

### 🔐 System Integration (sudo)
- Secure execution of server scripts
- Per-server isolation
- No cross-server interference

---

### 🌐 Web Interface
- Clean modern UI
- Responsive design (desktop & mobile)
- Dark mode ready

---

### 📊 Admin Dashboard
- Overview of all servers
- Quick actions
- Status monitoring

---

### 🔌 Plugin Support
- Extend functionality easily
- Compatible with XAseco plugins
- Custom integrations possible

---

### 🚀 Multi-Server Support
- Manage multiple servers independently
- Separate configs, logs, and control

---

### ⚡ Performance
- Node.js backend
- SQLite database
- Lightweight and fast

---

## 💡 Summary

**TrackMania Web Panel** is an all-in-one solution to manage your TrackMania servers without needing FTP or complex SSH commands.

Everything you need:
- Server control
- File management
- Logs
- Backups
- Multi-server support

All in one clean interface.

---

## 🛠️ Requirements

- Node.js
- npm
- Linux server (recommended for full control)
- TrackMania dedicated server files

---

## ▶️ Quick Start

```bash
cd /home/panel
chmod +x install-panel.sh
./install-panel.sh

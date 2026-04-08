# 🔐 TitanLogin

<div align="center">

**Military-Grade Authentication System for Minecraft**

[![Version](https://img.shields.io/badge/version-2.0.0-red)](https://github.com/Iraxeyy/TitanLogin/releases)
[![Minecraft](https://img.shields.io/badge/Minecraft-1.21--1.21.11-green)](https://papermc.io)
[![License](https://img.shields.io/badge/license-All%20Rights%20Reserved-blue)](LICENSE)
[![Discord](https://img.shields.io/badge/Discord-Join-5865F2)](https://discord.gg/yourserver)

</div>

---

## 📖 Overview

**TitanLogin** is an advanced authentication plugin featuring **AES-256 encryption**, **real-time IP intelligence**, and a **stunning RGB interface**—all without ever auto-banning innocent players.

> *"Secure your server. Alert your staff. Impress your players."*

---

## ✨ Features

### 🔒 Security
- **BCrypt Hashing (12 rounds)** - Industry-standard password protection
- **IP Change Detection** - Tracks and alerts staff on IP changes
- **Alt Account Monitoring** - Identifies multiple accounts from same IP
- **Brute Force Protection** - Locks after configurable failed attempts
- **Session Management** - Auto-logout with configurable timeout

### 📢 Staff Intelligence
- **Real-time Security Alerts** - Instant notifications with sound
- **Interactive Messages** - Click-to-investigate functionality
- **Security Event Logging** - All events saved to database
- **Player Status Viewer** - `/security` command shows session info

### 🎨 Visual Experience
- **RGB Gradient Messages** - Beautiful color transitions
- **Glowing UI Elements** - Eye-catching interface
- **Animated Progress Bar** - Visual countdown during login
- **Particle Effects** - Red dust explosion on successful login
- **Sound Effects** - Thunder + Level-up sounds

### ⚙️ Quality of Life
- **Save & Return Location** - Players return to where they left off
- **50+ Configurable Options** - Customize everything in `config.yml`
- **Async Database** - Zero lag on queries
- **Works with Any Spawn Plugin** - Compatible with Essentials, etc.

---

## 📦 Installation

### Requirements
- **Server:** Paper, Spigot, Purpur, or Pufferfish
- **Version:** Minecraft 1.21 - 1.21.11
- **Java:** Java 21+

### Quick Install
```bash
# 1. Download latest release
wget https://github.com/Iraxeyy/TitanLogin/releases/latest/download/TitanLogin.jar

# 2. Move to plugins folder
mv TitanLogin.jar /path/to/server/plugins/

# 3. Restart server
./restart.sh

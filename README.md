# SafeLogin - Secure Password Manager

[![Version](https://img.shields.io/badge/version-1.0-blue.svg)](https://github.com/ecko2010/safelogin)
[![License](https://img.shields.io/badge/license-MIT-green.svg)](LICENSE)
[![Platform](https://img.shields.io/badge/platform-Windows-lightgrey.svg)](https://www.microsoft.com/windows)
[![.NET](https://img.shields.io/badge/.NET-6.0-purple.svg)](https://dotnet.microsoft.com/)

<div align="center">
  <img src="Assets/logo.png" alt="SafeLogin Logo" width="128" height="128">
  <h3>🔐 Your Digital Keys, Safely Stored</h3>
  <p><em>A secure, local password manager with advanced encryption</em></p>
</div>

---

## 📋 Table of Contents

### 🌍 Languages / اللغات
- [🇺🇸 English](README_EN.md) (Current)
- [🇸🇦 العربية](README_AR.md)
- [🇫🇷 Français](README_FR.md)
- [🇩🇪 Deutsch](README_DE.md)
- [🇨🇳 中文](README_CN.md)

### 📖 Contents
- [Overview](#-overview)
- [Features](#-features)
- [Version Information](#-version-information)
- [Internet Connectivity](#-internet-connectivity)
- [Technologies](#-technologies)
- [Installation](#-installation)
- [Quick Start](#-quick-start)
- [Security & Privacy](#-security--privacy)
- [Contributing](#-contributing)
- [Support](#-support)
- [FAQ](#-faq)
- [License](#-license)

---

## 🌟 Overview

**SafeLogin** is a secure, desktop password manager designed to keep your digital credentials safe and organized. Built with security-first principles, it stores all your passwords locally with military-grade encryption, ensuring your sensitive data never leaves your device.

### Why SafeLogin?

- 🔒 **100% Local Storage** - Your data stays on your device
- 🛡️ **Military-Grade Encryption** - AES-256 encryption
- 🎯 **User-Friendly** - Clean, intuitive interface
- 🚀 **Fast & Lightweight** - Quick access to your passwords
- 🔍 **Smart Search** - Find credentials instantly
- 📝 **Notes Support** - Add context to your passwords

---

## ✨ Features

### 🔐 Security Features
- **AES-256 Encryption** - Industry-standard encryption for all stored data
- **Local Storage Only** - No cloud dependency, complete privacy
- **Master Password Protection** - Single password to access all credentials
- **Secure Password Generation** - Built-in strong password generator
- **Auto-lock** - Automatic session timeout for security

### 📊 Data Management
- **Add/Edit/Delete** - Full CRUD operations for credentials
- **Smart Search** - Search by site, username, or notes
- **🔄 Bulk Operations** - Planned for future versions
- **🔄 Data Export** - Backup functionality planned for v2.0
- **Notes Support** - Add detailed notes to each credential

### 🎨 User Interface
- **English Interface** - Current interface is in English
- **Modern Design** - Clean, intuitive WPF interface
- **🔄 Dark/Light Themes** - Planned for future versions
- **Responsive Layout** - Adapts to different screen sizes
- **🔄 Arabic Interface** - Native Arabic language support planned for v2.0

### 🔧 Advanced Features
- **License Management** - Secure activation system
- **Error Logging** - Comprehensive error tracking
- **Data Validation** - Input validation and sanitization
- **🔄 Backup & Restore** - Planned for v2.0
- **🔄 Auto-Update** - Planned for v2.0

---

## 📊 Version Information

### 🚀 Version 1.0 (Current)
**Released:** December 2024

**Core Features:**
- ✅ Secure password storage with AES-256 encryption
- ✅ Add, edit, delete, and search credentials
- ✅ Notes support for additional context
- ✅ English user interface
- ✅ License activation system
- ✅ Local SQLite database
- ✅ Master password protection
- ✅ Error logging and validation

**Current Capabilities:**
- Store unlimited passwords locally
- Search across all credential fields
- Add detailed notes to each entry
- Secure data with military-grade encryption
- Clean, intuitive interface

### 🔮 Version 2.0 (Planned)
**Expected:** Q2 2025

**Upcoming Features:**
- 🔄 **Automatic Backup & Restore**
  - Scheduled automatic backups
  - Cloud storage integration (Google Drive, OneDrive)
  - One-click restore functionality
  - Encrypted backup files

- 🌐 **Cloud Synchronization**
  - Multi-device sync capability
  - End-to-end encryption
  - Conflict resolution
  - Offline mode support

- 🔄 **Auto-Update System**
  - Automatic update checks
  - Background downloads
  - Seamless installation
  - Release notes display

- 🛡️ **Enhanced Security**
  - Two-factor authentication
  - Biometric authentication
  - Security audit reports
  - Breach monitoring

- 📱 **Mobile Companion**
  - Android/iOS apps
  - QR code sync
  - Mobile-optimized interface
  - Cross-platform compatibility

---

## 🌐 Internet Connectivity

### Version 1.0 - Minimal Internet Usage

**When Internet is Required:**
- 🔑 **License Activation Only** - One-time activation process
- 🔄 **License Validation** - Periodic license verification

**When Internet is NOT Required:**
- 💾 **Daily Usage** - All core functionality works offline
- 🔍 **Search & Browse** - Complete offline access to your data
- ➕ **Add/Edit Credentials** - Full CRUD operations offline
- 🔐 **Password Access** - Instant access without internet

**Data Privacy:**
- ❌ **No Data Upload** - Your passwords never leave your device
- ❌ **No Analytics** - No usage tracking or data collection
- ❌ **No Ads** - Clean, ad-free experience
- ✅ **Complete Privacy** - Your data remains 100% private

### Version 2.0 - Optional Internet Features

**Optional Internet Features:**
- ☁️ **Cloud Backup** - Optional cloud storage for backups
- 🔄 **Auto-Updates** - Automatic update downloads
- 🔄 **Sync** - Multi-device synchronization
- 🛡️ **Breach Monitoring** - Check for compromised passwords

**Always Offline Capable:**
- 💾 **Core Functionality** - All essential features work offline
- 🔐 **Password Access** - Instant access to stored credentials
- 🔍 **Search** - Full search capabilities offline
- 📝 **Data Management** - Add, edit, delete without internet

---

## 🛠️ Technologies

### Core Technologies
- **C# (.NET 6)** - Modern, cross-platform framework
- **WPF (Windows Presentation Foundation)** - Rich desktop UI
- **SQLite** - Lightweight, embedded database
- **MVVM Pattern** - Clean architecture and separation of concerns

### Security Libraries
- **System.Security.Cryptography** - AES-256 encryption
- **BCrypt.Net** - Secure password hashing
- **System.Text.Json** - Secure data serialization

### Development Tools
- **Visual Studio 2022** - Primary IDE
- **Git** - Version control
- **NuGet** - Package management
- **Inno Setup** - Windows installer creation

---

## 💻 Installation

### System Requirements
- **Operating System:** Windows 10/11 (64-bit)
- **.NET Runtime:** .NET 6.0 or later
- **Memory:** 512 MB RAM minimum
- **Storage:** 100 MB available space
- **Display:** 1024x768 minimum resolution

### Installation Methods

#### Method 1: Installer (Recommended)
1. Download `SafeLogin_Installer.exe` from releases
2. Run the installer as administrator
3. Follow the installation wizard
4. Launch SafeLogin from Start Menu

#### Method 2: Portable Version
1. Download `SafeLogin.zip` from releases
2. Extract to your preferred location
3. Run `SafeLogin.exe` directly
4. No installation required

#### Method 3: Build from Source
```bash
# Clone the repository
git clone https://github.com/ecko2010/safelogin.git
cd safelogin

# Restore dependencies
dotnet restore

# Build the project
dotnet build --configuration Release

# Run the application
dotnet run --project UserNamePassword
```

---

## 🚀 Quick Start

### First Launch
1. **Launch SafeLogin** from your Start Menu or desktop
2. **Enter License Key** - Activate your copy (internet required)
3. **Create Master Password** - This protects all your data
4. **Start Adding Passwords** - Begin securing your credentials

### Adding Your First Password
1. Click **"Add New"** button
2. Enter **Website/Service** name
3. Enter your **Username**
4. Enter your **Password**
5. Add **Notes** (optional)
6. Click **"Save"**

### Searching Passwords
- Use the **search box** at the top
- Search by **website**, **username**, or **notes**
- Results update in real-time

### Editing Passwords
1. **Double-click** any credential in the list
2. Modify the information
3. Click **"Save"** to update

---

## 🔒 Security & Privacy

### Our Security Commitments

#### 🛡️ What We Protect
- **All Passwords** - Encrypted with AES-256
- **Personal Notes** - Fully encrypted storage
- **User Data** - Complete local storage
- **Master Password** - Securely hashed with BCrypt

#### 🚫 What We DON'T Collect
- **No Usage Analytics** - We don't track how you use the app
- **No Personal Data** - Your information stays on your device
- **No Password Data** - Your passwords never leave your computer
- **No Browsing History** - We don't monitor your web activity

#### 🔐 Encryption Details
- **Algorithm:** AES-256-GCM
- **Key Derivation:** PBKDF2 with 100,000 iterations
- **Salt:** Unique salt for each encryption
- **Authentication:** Built-in integrity verification

### Best Practices

#### 🎯 For Maximum Security
1. **Strong Master Password** - Use a unique, complex password
2. **Regular Backups** - Export your data periodically
3. **Keep Updated** - Install updates promptly
4. **Secure Environment** - Use on trusted devices only
5. **Lock When Away** - Enable auto-lock feature

#### ⚠️ Important Notes
- **Master Password Recovery** - We cannot recover forgotten master passwords
- **Data Backup** - You are responsible for backing up your data
- **Device Security** - Ensure your device is secure and updated

---

## 🤝 Contributing

We welcome contributions from the community! Here's how you can help:

### Ways to Contribute
- 🐛 **Report Bugs** - Help us identify and fix issues
- 💡 **Suggest Features** - Share your ideas for improvements
- 🌍 **Translations** - Help localize the app
- 📖 **Documentation** - Improve our guides and docs
- 💻 **Code Contributions** - Submit pull requests

### Development Setup
1. Fork the repository
2. Clone your fork locally
3. Create a feature branch
4. Make your changes
5. Test thoroughly
6. Submit a pull request

### Coding Standards
- Follow C# coding conventions
- Use meaningful variable names
- Add comments for complex logic
- Include unit tests for new features
- Maintain MVVM architecture

---

## 📞 Support

### Getting Help

#### 📧 Contact Options
- **Telegram Group:** [Join Support Group](https://t.me/SafeLoginSupport)
- **GitHub Issues:** [Report bugs or request features](https://github.com/ecko2010/safelogin/issues)
- **Documentation:** Check our comprehensive guides

#### 🕐 Response Times
- **Bug Reports:** Within 24-48 hours
- **Feature Requests:** Within 1 week
- **General Questions:** Within 24 hours

### Before Contacting Support
1. Check the [FAQ section](#-faq)
2. Search existing GitHub issues
3. Try restarting the application
4. Check if you're using the latest version

---

## ❓ FAQ

### General Questions

**Q: Is SafeLogin free?**
A: SafeLogin requires a license for full functionality. We offer trial periods and educational discounts.

**Q: Can I use SafeLogin offline?**
A: Yes! After initial license activation, SafeLogin works completely offline.

**Q: How secure is my data?**
A: Your data is encrypted with AES-256 and stored locally. We cannot access your passwords.

**Q: Can I sync across devices?**
A: Multi-device sync will be available in Version 2.0. Currently, you can export/import data manually.

### Technical Questions

**Q: What if I forget my master password?**
A: Unfortunately, we cannot recover forgotten master passwords due to our security design. Always keep a secure backup.

**Q: Can I export my data?**
A: Yes, you can export your data for backup purposes. The export is encrypted for security.

**Q: Does SafeLogin work on Mac/Linux?**
A: Currently Windows only. Cross-platform support is planned for future versions.

**Q: How do I update SafeLogin?**
A: Manual updates for now. Automatic updates coming in Version 2.0.

### Troubleshooting

**Q: The app won't start**
A: Ensure .NET 6.0 is installed and try running as administrator.

**Q: I can't activate my license**
A: Check your internet connection and firewall settings. Contact support if issues persist.

**Q: My data disappeared**
A: Check if the database file exists in the app directory. Restore from backup if available.

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

### Third-Party Licenses
- **.NET Framework** - Microsoft License
- **SQLite** - Public Domain
- **BCrypt.Net** - MIT License

---

<div align="center">
  <h3>🔐 SafeLogin - Your Digital Security, Simplified</h3>
  <p><em>Built with ❤️ for secure password management</em></p>
  
  <p>
    <a href="#-overview">Overview</a> •
    <a href="#-features">Features</a> •
    <a href="#-installation">Installation</a> •
    <a href="#-support">Support</a>
  </p>
  
  <p><strong>Version 1.0</strong> | <em>December 2024</em></p>
</div>

---

*Last updated: December 2024*
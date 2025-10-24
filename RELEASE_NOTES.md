# WhatsApp Lock Manager v2.5.0

## 🎉 Initial Public Release

This is the first public release of WhatsApp Lock Manager - a powerful Windows application to control access to WhatsApp Desktop and WhatsApp Web with PIN protection.

## 📸 Screenshots

<div align="center">
  <img src="Images/app_1.png" alt="WhatsApp Lock Manager - Main Interface" width="400"/>
  <img src="Images/pin.png" alt="PIN Setup" width="400"/>
  <img src="Images/app_2.png" alt="Lock Status" width="400"/>
</div>

## 📦 What's Included

- **Full installer with .NET 8 runtime** (~52 MB)
- **Self-contained deployment** - No additional software needed
- **User documentation** included in installer
- **Hidden security components** with restricted permissions

## ✨ Key Features

### 🔐 WhatsApp Desktop Locking
- System-level file permission control
- Automatic WhatsApp process detection and termination
- Persistent locks that survive reboots
- Safe ACL backup and restore mechanism

### 🌐 WhatsApp Web Blocking
- Hosts file manipulation to block web.whatsapp.com domains
- Automatic browser tab closure
- Support for Chrome, Edge, Firefox, and other browsers
- Clean restore on unlock

### 🔑 Security Features
- 6-digit PIN protection
- SYSTEM-level privilege elevation via PsExec
- Hidden support files with read-only permissions
- Encrypted configuration storage
- Activity logging with timestamps

### 🎨 User Interface
- Modern WPF design
- Real-time status indicators
- Color-coded feedback (green = unlocked, red = locked)
- Intuitive button layout
- Comprehensive error messages

## 📥 Installation

1. Download `WhatsAppLockManager_Setup_2.5.0.exe` from assets below
2. Run the installer (requires administrator privileges)
3. Follow the setup wizard
4. Read the mandatory User Guide and Privacy Statement
5. Launch the application from Start Menu or Desktop shortcut

## ⚙️ Technical Specifications

- **Platform:** Windows 10/11 (64-bit only)
- **Framework:** .NET 8.0 WPF
- **Deployment:** Self-contained with runtime included
- **Size:** ~52 MB (installer), ~150 MB (installed)
- **Dependencies:** PSTools (PsExec) included
- **Privileges:** Administrator required

## 📋 System Requirements

- Windows 10 version 1809 or later (64-bit)
- Windows 11 (64-bit)
- Administrator account
- ~150 MB free disk space
- WhatsApp Desktop installed (for app locking feature)

## 🛠️ What Gets Installed

**Visible Components:**
- Main application executable
- Launch batch file with UAC elevation
- User documentation (User Guide, Privacy Statement, Visual Guide)
- Application icon
- Start Menu shortcuts (app + publisher links)
- Desktop shortcut (optional, checked by default)

**Hidden Components (for security):**
- Manager script/executable (compiled PowerShell)
- PSTools suite (PsExec for SYSTEM elevation)
- Helper scripts
- All with restricted read+execute permissions

## ⚠️ Important Notes

### First-Time Setup
- Set a 6-digit PIN on first launch
- **Do not forget your PIN** - recovery requires manual config file editing
- Test locking/unlocking to ensure proper operation

### Security Considerations
- Requires administrator privileges to function
- Uses SYSTEM-level privileges for robust protection
- Locks persist across reboots until manually unlocked
- PIN stored locally in encrypted format

### Antivirus Warnings
Some antivirus software may flag the installer due to:
- **PsExec.exe** - Legitimate Sysinternals tool (false positive)
- **Admin privileges** - Required for system-level operations
- **Unsigned executable** - Code signing certificate not yet applied

The software is safe - all components are legitimate Windows administration tools.

## 🐛 Known Issues

- None reported yet - this is the first release!

## 📞 Support

If you encounter issues:
1. Check the included User Guide
2. Review the Troubleshooting section in README.md
3. Contact developer via GitHub, LinkedIn, or CodeTime (links in app)

## 🔄 Future Plans

- Code signing certificate for trusted publisher status
- Auto-update functionality
- Multiple PIN support for family accounts
- Scheduled auto-lock feature
- Biometric unlock support (Windows Hello)

## 🙏 Acknowledgments

- Microsoft Sysinternals for PSTools
- .NET team for WPF framework
- Inno Setup for installer creation
- PS2EXE for PowerShell compilation

---

**Developed by creativepurus**
- 💻 GitHub: [@creativepurus](https://github.com/creativepurus)
- 💼 LinkedIn: [@creativepurus](https://linkedin.com/in/creativepurus)
- ⏱️ CodeTime : [#creativepurus](https://codetime.dev/en/user/17354)

## 📜 License

This software is provided as-is for personal use. See Privacy Statement included with installation for full terms.


<!-- Thanks for your Visit -->
<div align="center">
  <a href="https://git.io/typing-svg">
    <img
      alt="Thanks for your visit ❤️"
      src="https://readme-typing-svg.demolab.com?font=Roboto+Slab&size=24&pause=1000&color=7E3ACE&center=true&vCenter=true&width=520&lines=Thanks+for+your+visit+%E2%9D%A4%EF%B8%8F" />
  </a>
    <img src="https://tenor.com/view/bjyx-wyb-wang-yibo-finger-heart-heart-gif-15749379.gif" alt="Finger Heart GIF"/>
</div>

<br>

<p align="center">
  <a href="https://linkedin.com/in/creativepurus/">
    <img src="https://img.shields.io/badge/-Connect%20on%20Linkedin-blue?style=for-the-badge&logo=linkedin" alt="Connect on LinkedIn">
  </a>
</p>

<p align="center">
  <a href="https://github.com/sponsors/creativepurus/" title="Anand Purushottam's GitHub Sponsorship Profile">
    <img src="https://img.shields.io/badge/-❤️%20Sponsor%20me%20on%20GitHub-green?style=for-the-badge&logo=github" alt="Sponsor me on GitHub">
  </a>
</p>


**Made with ❤️ by 💻 [@creativepurus](https://linkedin.com/in/creativepurus) 🇮🇳**

<!-- Back to TOP -->
<p align="right">
  <a href="#top">
    <img src="https://img.shields.io/static/v1?label&message=Back+to+Top&color=red&style=for-the-badge&logo" alt="Back to Top" />
  </a>
</p>

<!-- Footer -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&height=100&section=footer" alt="Footer"/>
</p>
# React2Shell Ultimate Scanner v2.0

**Professional Next.js RSC RCE Vulnerability Scanner for CVE-2025-66478**

[![Version](https://img.shields.io/badge/version-2.0.0-blue.svg)](https://github.com/hackersatyamrastogi/react2shell-ultimate/releases/tag/v2.0.0)
[![Python](https://img.shields.io/badge/python-3.8+-green.svg)](https://www.python.org/)
[![License](https://img.shields.io/badge/license-MIT-orange.svg)](LICENSE)
[![Stars](https://img.shields.io/github/stars/hackersatyamrastogi/react2shell-ultimate?style=social)](https://github.com/hackersatyamrastogi/react2shell-ultimate)

## 🎯 Overview

React2Shell Ultimate is a comprehensive vulnerability scanner for CVE-2025-66478 - a critical Remote Code Execution (RCE) vulnerability affecting Next.js applications using React Server Components (RSC).

## 🆕 What's New in v2.0

Version 2.0 brings major enhancements and professional features:

- ✨ **Enhanced God Mode** - Advanced exploitation capabilities with improved command execution
- 🚀 **Better WAF Bypass** - More sophisticated techniques to evade security controls
- 🎨 **Professional Web Platform** - Full-featured web interface at [www.react2shellscanner.com](https://www.react2shellscanner.com)
- 🔧 **Improved Error Handling** - Better debugging and output display
- 📚 **Professional Documentation** - Comprehensive guides and API documentation
- 🛡️ **Security Best Practices** - Enhanced safety features and warnings

## ✨ Features

- 🔍 Multiple Scan Modes (Safe, RCE, Version, Comprehensive)
- 🛡️ Advanced WAF Bypass Techniques
- ⚡ God Mode: Interactive Shell & File Reading
- 🎯 Batch Scanning with Threading
- 📊 JSON Output for Automation
- 🔒 Safe Mode for Non-Invasive Detection

## 🚀 Quick Start

```bash
# Basic scan
python3 react2shell-ultimate.py -u https://target.com

# RCE mode
python3 react2shell-ultimate.py -u https://target.com --mode rce

# Execute command (God Mode)
python3 react2shell-ultimate.py -u https://target.com --exec "id"

# Interactive shell
python3 react2shell-ultimate.py -u https://target.com --shell
```

## 📦 Installation

```bash
# Clone the repository
git clone https://github.com/hackersatyamrastogi/react2shell-ultimate.git
cd react2shell-ultimate

# Install dependencies
pip3 install -r requirements.txt

# Make the script executable
chmod +x react2shell-ultimate.py

# Verify installation
python3 react2shell-ultimate.py --version
```

**Requirements:**
- Python 3.8 or higher
- requests >= 2.31.0
- urllib3 >= 2.0.0
- tqdm >= 4.65.0

## 🌐 Web Platform

Experience React2Shell Ultimate through our professional web interface:

- **🌐 Live Scanner:** [www.react2shellscanner.com](https://www.react2shellscanner.com)
- **🔌 API Endpoint:** [api.react2shellscanner.com](https://api.react2shellscanner.com)

**Web Features:**
- Interactive vulnerability scanner
- Real-time command execution (God Mode)
- Scan history and batch operations
- Professional admin dashboard

## ⚠️ Legal Disclaimer

**FOR AUTHORIZED SECURITY TESTING ONLY**

This tool is designed for:
- Authorized penetration testing
- Bug bounty programs
- Security research
- Educational purposes

**You are fully responsible for any misuse of this tool.**

## 📋 Version History

### v2.0.0 (December 2025)
- Enhanced God Mode exploitation capabilities
- Improved WAF bypass techniques
- Better error handling and output display
- Professional web platform integration
- Comprehensive documentation updates
- Security best practices implementation

### v1.1.0 (December 2025)
- Initial public release
- Core scanning functionality
- Basic God Mode features
- Multi-mode detection support

## 👨‍💻 Author

**Satyam Rastogi**

- 🌐 Website: [satyamrastogi.com](https://www.satyamrastogi.com)
- 💼 GitHub: [@hackersatyamrastogi](https://github.com/hackersatyamrastogi)
- 🐦 Twitter: [@hackersatyamrastogi](https://twitter.com/hackersatyamrastogi)

---

**Made with ❤️ by Satyam Rastogi**

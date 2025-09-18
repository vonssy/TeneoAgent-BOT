# 🔗 Teneo Agent Insights BOT

> Automated Teneo Agent Insights node management with multi-threading and advanced proxy support

[![Python Version](https://img.shields.io/badge/python-3.9+-blue.svg)](https://www.python.org/downloads/)
[![License](https://img.shields.io/badge/license-MIT-green.svg)](LICENSE)
[![Price](https://img.shields.io/badge/price-$5-brightgreen.svg)](https://t.me/vonssy_2nd)

## 📋 Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Requirements](#requirements)
- [Installation](#installation)
- [Configuration](#configuration)
- [Setup & Usage](#setup--usage)
- [Proxy Recommendation](#proxy-recommendation)
- [Purchase](#purchase)
- [Support](#support)
- [Contributing](#contributing)

## 🎯 Overview

Teneo Agent Insights BOT is a premium automated tool designed to manage Teneo Agent Insights nodes efficiently with multi-threading support. It provides seamless integration with free and private proxies, automated token extraction, and connection management with Agent Insights Node Extension.

**💰 Price:** Only $5  
**📞 Contact:** [Vonssy on Telegram](https://t.me/vonssy_2nd)

> **⚠️ Important:** You need access to Teneo Agent Insights to use this bot.

## ✨ Features

- 🔄 **Automated Account Management** - Retrieve account information automatically
- 🌐 **Flexible Proxy Support** - Run with or without proxy configuration
- 🔀 **Smart Proxy Rotation** - Automatic rotation of invalid proxies
- 🔌 **Extension Integration** - Auto-connect with Agent Insights Node Extension
- ⚡ **Multi-Threading Support** - Handle multiple accounts simultaneously
- 🛡️ **Advanced Security** - Multiple proxy layers for enhanced protection

## 📋 Requirements

- **Python:** Version 3.9 or higher
- **pip:** Latest version recommended
- **Teneo Access:** Must have access to Teneo Agent Insights
- **2captcha Key:** Optional (for automated captcha solving)

## 🛠 Installation

### 1. Extract the Archive

```bash
unzip TeneoAgent-BOT.zip
cd TeneoAgent-BOT
```

### 2. Install Dependencies

```bash
pip install -r requirements.txt
# or for Python 3 specifically
pip3 install -r requirements.txt
```

## ⚙️ Configuration

### 2captcha Key Setup (Optional)

Create or edit `2captcha_key.txt` in the project directory:

```
your_2captcha_key
```

### Account Configuration

Create or edit `accounts.json` in the project directory:

```json
[
    {
        "Email": "your_email_address_1",
        "Password": "your_password_1"
    },
    {
        "Email": "your_email_address_2",
        "Password": "your_password_2"
    }
]
```

### Automatic Token Generation

The bot can automatically fetch access tokens using your 2captcha key through the setup script.

### Manual Token Setup (Alternative)

If you prefer to fetch tokens manually or don't have a 2captcha key, you can extract access tokens from the Teneo dashboard:

<div align="center">
  <img src="images/example.png" alt="Teneo Access Token Example" width="500">
  <p><em>Example of extracting access tokens manually using browser developer tools</em></p>
</div>

Create or edit `tokens.json`:

```json
[
    {
        "Email": "your_email_address_1",
        "accessToken": "your_access_token_1"
    },
    {
        "Email": "your_email_address_2",
        "accessToken": "your_access_token_2"
    }
]
```

### Proxy Configuration (Optional)

Create or edit `proxy.txt` in the project directory:

```
# Simple format (HTTP protocol by default)
192.168.1.1:8080

# With protocol specification
http://192.168.1.1:8080
https://192.168.1.1:8080

# With authentication
http://username:password@192.168.1.1:8080
```

## 🚀 Setup & Usage

### Automatic Token Setup (Recommended)

Run the setup script to automatically fetch access tokens using your configured 2captcha key and account credentials:

```bash
python setup.py
# or for Python 3 specifically
python3 setup.py
```

> **💡 What does setup.py do?**
> - Automatically logs in to your Teneo Agent Insights accounts
> - Solves captchas using your 2captcha key
> - Extracts access tokens automatically
> - Saves tokens to `tokens.json` for the bot to use

### Start the Bot

After running the setup, launch the Teneo Agent Insights BOT:

```bash
python bot.py
# or for Python 3 specifically
python3 bot.py
```

### Runtime Options

When starting the bot, you'll be prompted to choose:

1. **Proxy Mode Selection:**
   - Option `1`: Run with proxies
   - Option `2`: Run without proxy

2. **Auto-Rotation:** 
   - `y`: Enable automatic invalid proxy rotation
   - `n`: Disable auto-rotation

## 🌐 Proxy Recommendation

<div align="left">
  <img src="images/banner.png" alt="NST Proxy Banner" width="300">
</div>

For reliable multi-wallet automation and geo-restriction bypass, we recommend **Nstproxy**:

### Why Nstproxy?
- 💰 **Affordable pricing** starting from $0.1/GB
- 🌍 **Global coverage** with multiple locations
- 🔄 **Advanced rotation control**
- 🛡️ **Anti-ban technology**

### Get Started with Nstproxy
- 🔗 **Website:** [Nstproxy.com](https://www.nstproxy.com/?utm_source=vonssy)
- 💬 **Telegram:** [@nstproxy](https://t.me/nstproxy)
- 🎮 **Discord:** [Join Server](https://discord.gg/5jjWCAmvng)
- 📚 **GitHub:** [Nstproxy Repository](https://github.com/Nstproxy)

> 🎁 **Special Offer:** Use code `VONSSY` for **10% OFF** your first purchase!

## 💰 Purchase

This is a **premium bot** available for purchase:

### 💵 Pricing
- **Price:** Only **$5** 
- **Payment:** Contact via Telegram
- **Support:** Included with purchase

### 📞 How to Purchase
1. **Contact:** [Vonssy on Telegram](https://t.me/vonssy_2nd)
2. **Payment:** Complete payment process
3. **Delivery:** Receive bot files and setup instructions
4. **Support:** Get assistance with setup and usage

### ✅ What's Included
- ✅ Complete bot source code
- ✅ Setup instructions
- ✅ Configuration templates
- ✅ Basic support
- ✅ Future updates

## 💖 Support the Project

If this project has been helpful to you, consider supporting its development:

### Cryptocurrency Donations

| Network | Address |
|---------|---------|
| **EVM** | `0xe3c9ef9a39e9eb0582e5b147026cae524338521a` |
| **TON** | `UQBEFv58DC4FUrGqinBB5PAQS7TzXSm5c1Fn6nkiet8kmehB` |
| **SOL** | `E1xkaJYmAFEj28NPHKhjbf7GcvfdjKdvXju8d8AeSunf` |
| **SUI** | `0xa03726ecbbe00b31df6a61d7a59d02a7eedc39fe269532ceab97852a04cf3347` |

## 🤝 Contributing

We welcome contributions from the community! Here's how you can help:

1. ⭐ **Star this repository** if you find it useful
2. 👥 **Follow** for updates on new features
3. 🐛 **Report issues** via GitHub Issues
4. 💡 **Suggest improvements** or new features
5. 🔧 **Submit pull requests** for bug fixes or enhancements

## 📞 Contact & Support

- **Developer:** vonssy
- **Purchase:** [Telegram @vonssy_2nd](https://t.me/vonssy_2nd)
- **Issues:** [GitHub Issues](https://github.com/vonssy/TeneoAgent-BOT/issues)
- **Discussions:** [GitHub Discussions](https://github.com/vonssy/TeneoAgent-BOT/discussions)

---

<div align="center">

**Made with ❤️ by [vonssy](https://github.com/vonssy)**

*Thank you for your interest in Teneo Agent Insights BOT!*  
*Contact [@vonssy_2nd](https://t.me/vonssy_2nd) to purchase for only $5*

</div>
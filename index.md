---
layout: "default"
title: "🌟 mimo2api - Simple API for Mimo AI Integration"
description: "🤖 Transform Xiaomi Mimo AI into an OpenAI-compatible API for deep thinking applications, making integration smooth and effective."
---
# 🌟 mimo2api - Simple API for Mimo AI Integration

## 🚀 Getting Started

Welcome to the Mimo2API! This application allows you to easily convert Xiaomi Mimo AI into an OpenAI compatible API. Whether you want to explore deep thinking or enhance your AI projects, this tool is designed for you.

[![Download Mimo2API](https://img.shields.io/badge/Download%20Mimo2API-v1.0-brightgreen)](https://github.com/leookun/mimo2api/releases)

## 📥 Download & Install

To get started, follow the instructions based on your operating system. You can choose between downloading the precompiled binaries or compiling from source.

### 🖥️ Option 1: Download Precompiled Binaries

You can easily download the precompiled versions of Mimo2API for your system from the [Releases page](https://github.com/leookun/mimo2api/releases).

#### **Linux:**
1. Open your terminal.
2. Run the following commands:
   ```bash
   curl -LO https://github.com/leookun/mimo2api/releases/latest/download/mimo2api-linux-amd64
   chmod +x mimo2api-linux-amd64
   ./mimo2api-linux-amd64
   ```

#### **macOS (Intel):**
1. Open your terminal.
2. Run the following commands:
   ```bash
   curl -LO https://github.com/leookun/mimo2api/releases/latest/download/mimo2api-darwin-amd64
   chmod +x mimo2api-darwin-amd64
   sudo xattr -cr mimo2api-darwin-amd64  # Removes security limitations
   ./mimo2api-darwin-amd64
   ```

#### **macOS (Apple Silicon):**
1. Open your terminal.
2. Run the following commands:
   ```bash
   curl -LO https://github.com/leookun/mimo2api/releases/latest/download/mimo2api-darwin-arm64
   chmod +x mimo2api-darwin-arm64
   sudo xattr -cr mimo2api-darwin-arm64  # Removes security limitations
   ./mimo2api-darwin-arm64
   ```

#### **Windows:**
1. Visit the [Releases page](https://github.com/leookun/mimo2api/releases) and download `mimo2api-windows-amd64.exe`.
2. Double click to run it, or you can execute it from the command line.

### ⚙️ Option 2: Compile from Source

If you prefer to compile the source code, follow these steps:

1. Open your terminal or command prompt.
2. Run the following commands:
   ```bash
   git clone https://github.com/leookun/mimo2api.git
   cd mimo2api
   go build -o mimo2api .
   ./mimo2api
   ```

## ⚡ How to Run Mimo2API

After successfully installing Mimo2API, you can run it with the following command:

```bash
# Default port 8080
./mimo2api

# To specify a different port, use this command
PORT=3000 ./mimo2api
```

## 📊 Features

Mimo2API offers various features to enhance your AI integration experience:

- **Compatibility**: Works seamlessly with OpenAI tools.
- **Flexible Port Settings**: Choose your own port for easier setup.
- **Cross-Platform**: Available for Linux, macOS, and Windows.

## 📝 Usage Tips

- Always ensure that you are running the tool with the necessary permissions.
- For macOS users, remove security restrictions as needed.
- Maintain the correct version of Go installed to compile from source.

For further queries and issues, feel free to check the project's [issues page](https://github.com/leookun/mimo2api/issues) for support. Happy coding!
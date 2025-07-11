# NEX – Nearby Exchange 🚀

> **Real-time, P2P LAN chat with encrypted messaging and file transfer**

![NEX Logo](./assets/logo.png)

## Table of Contents
1. [About](#about)
2. [Features](#features)
3. [Getting Started](#getting-started)
   - [Prerequisites](#prerequisites)
   - [Installation](#installation)
   - [Running the App](#running-the-app)
4. [Usage](#usage)
   - [Peer Discovery](#peer-discovery)
   - [Chat & File Transfer](#chat--file-transfer)
5. [Architecture](#architecture)
6. [Security](#security)
7. [Roadmap](#roadmap)
8. [Contributing](#contributing)
9. [License](#license)

---

## About
NEX (Nearby Exchange) is a desktop application built with Python and PyQt, enabling users on the same local network to chat and share files securely, without any internet dependency.

## Features
- **Peer-to-peer Messaging**: Discover users via mDNS/UDP or connect manually via IP.
- **Encrypted Chats**: End-to-end encryption using libsodium.
- **File Transfer**: Send and receive files with progress indicators.
- **Custom Usernames**: Set how you appear to others.
- **Status Indicators**: Online (app active) and Idle (app background).
- **Cross-Platform**: Windows, macOS, and Linux (AppImage).

## Getting Started
### Prerequisites
- Python 3.9+
- Qt 5 or 6 (via PyQt or PySide)
- Git

### Installation
```bash
# Clone the repo
git clone https://github.com/awanicaleb/nex.git
cd nex

# Create a virtual environment
python -m venv venv
source venv/bin/activate    # macOS/Linux
venv\\Scripts\\activate   # Windows

# Install dependencies
pip install -r requirements.txt

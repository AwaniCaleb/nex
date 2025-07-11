# Roadmap

This document outlines the planned development milestones for **NEX (Nearby Exchange)**:

## MVP: Core Functionality (Weeks 1–4)
- **Peer Discovery**: mDNS/UDP broadcast and manual IP connect.
- **Real-Time Chat**: One-to-one messaging via ZeroMQ.
- **Basic UI**: PyQt interface for peer list and chat window.

## Phase 2: Enhanced Features (Weeks 5–6)
- **File Transfer**: Send and receive files with progress indicators.
- **Custom Usernames**: Users set display names.
- **Status Indicators**: Online/idle states and join/leave notifications.

## Phase 3: Security & Storage (Weeks 7–8)
- **Key Management**: CLI helper for public/private key generation.
- **Key Exchange**: QR-code interface for secure identity exchange.
- **Encryption**: Authenticated encryption (libsodium) for messages.
- **Persistent Storage**: Encrypted SQLite integration for chat history.

## Phase 4: Packaging & Deployment (Weeks 9–10)
- **Desktop Builds**: PyInstaller configs for Windows, macOS, Linux.
- **AppImage**: Single-file Linux distribution.
- **Updater**: In-app update checks when online.
- **Documentation**: Detailed install and upgrade guides.

## Ongoing
- **CI/CD**: GitHub Actions for linting, testing, and GUI checks.
- **Code Reviews**: Mandatory PR reviews and pair-programming sessions.
- **Community**: Issue triage, feature discussions, and support.

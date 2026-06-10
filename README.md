# 🌌 Matrix CE: Infrastructure & Auth Core

## 📋 Overview
The backbone of the KAI 9000 Matrix ecosystem, providing centralized API services, background automation, and secure authentication lifecycle management.

## 🏗️ Core Components
- **Qwen Pedagogy Server**: `qwen_pedagogy_server.py` - The primary local LLM hook and training orchestration server.
- **Hive Daemon**: `hive_daemon.py` - Manages all autonomous loops (Gmail harvesting, heartbeat monitoring).
- **KQML Router**: `kqml_router.py` - A formal postmaster for agent-to-agent communication.
- **Universal OAuth Refresh**: `refresh_tokens.sh` - Lightweight rotation logic for GitHub/Google tokens.

## 🛡️ Security & Watchdogs
- **Anti-Hang Watchdog**: Prevents I/O blocking during heavy inference.
- **Secure Vault**: Management of API keys and project-specific secrets.

## 🚀 Deployment
Run `python3 hive_daemon.py` to initialize all background services.

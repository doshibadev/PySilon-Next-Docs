---
sidebar_position: 3
---

# Setup & Installation

Follow these steps to get PySilon-Next up and running.

## Prerequisites
*   **Python 3.10+**: Ensure you have a modern version of Python installed.
*   **Git**: Required to clone the repository.
*   **Discord Account**: You need a Discord account to create the bot and server.

## 1. Clone the Repository

Open your terminal or command prompt and run:

```bash
git clone https://github.com/doshibadev/PySilon-Next
cd PySilon-Next
```

## 2. Create Discord Bot & Server

You need a dedicated Discord server and Bot to control your targets.

1.  Go to the [Discord Developer Portal](https://discord.com/developers/applications).
2.  Create a **New Application**.
3.  Go to the **Bot** tab and click **Add Bot**.
4.  Enable **Message Content Intent**, **Server Members Intent**, and **Presence Intent** under "Privileged Gateway Intents".
5.  Copy your **Bot Token** (you will need this later).
6.  Invite the bot to your server using the **OAuth2** URL generator (Select `bot` scope and `Administrator` permissions).
7.  Enable **Developer Mode** in your personal Discord settings (User Settings -> Advanced -> Developer Mode).
8.  Right-click your server name and **Copy ID**.

## 3. Build the RAT

PySilon-Next comes with a builder to make configuration easy.

### Windows
Run the batch file directly:
```cmd
PySilon.bat
```
Or via command line:
```cmd
./PySilon.bat
```

### Linux
Run the shell script:
```bash
bash PySilon-linux.sh
```

The builder will guide you through:
*   Installing dependencies.
*   Entering your Bot Token and Guild ID.
*   Selecting features to enable.
*   Compiling the executable (optional).

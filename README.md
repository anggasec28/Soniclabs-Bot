# Soniclabs-Bot
## Installation

### For Linux

1. Open your `Terminal`.

1. clone the repo and install dependencies

   ```bash
   git clone https://github.com/web3bothub/soniclabs-arcade-bot.git
   cd Soniclabs-Bot
   npm install
   ```

1. configure your accounts

   ```bash
   cp .env.example .env
   nano .env
   ```

> [!tip]
> Please read the comments in `.env` file and fill in the required information.

1. start the bot

    ```bash
    npm run start
    ```

### For Windows

1. Open your `Command Prompt` or `Power Shell`.
1. clone the repo and install dependencies

   ```bash
   git clone https://github.com/web3bothub/soniclabs-arcade-bot.git
   cd Soniclabs-Bot
   npm install
   ```

1. Navigate to `soniclabs-arcade-bot` directory.
1. cp `.env.example` to file `.env`
1. Now open `.env` and config your account private key or mnemonic, and optionally you can add proxy for each account.
1. Back to `soniclabs-arcade-bot` directory.
1. In your `Command Prompt` or `Power Shell`, run the bot:

    ```bash
    node src/index.js
    ```

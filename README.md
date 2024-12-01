# KAISAR NETWORK

Your compute, your currency
Transform your compute power into real earnings

![banner](image.png)

# Kaisar Beta Cli Mode

## Features

- Support Multy accounts.
- Support Proxy.

## Requirements

- Node.js 20+
- Dependencies installed via `npm install`

## Files

- **if you already have account you can create file manually**
- `tokens.txt`: Stores access_tokens each line 1 account.
- `id.txt`: Stores Extension IDs each line 1 account.
- `proxy.txt`: stores Proxy url format `http://user:pass@ip:port` each line 1 proxy.
- **if you register using cli, file above auto filled, just fill `email.txt` with your email.**
- `emails.txt`: Store email account 1 line 1 account.

## Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/raymundedgar/kaisar-bot.git
   cd kaisar-bot
   ```
2. install dependencies:
   ```bash
   npm install
   ```
3. Edit `emails.txt` file
   ```
   nano emails.txt
   ```

4. Edit `proxy.txt` if you want to use proxy, otherwise, leave it as it is.
   ```
   nano proxy.txt
   ```

5. Run below code **TWICE** if you are going to **register** a new account. If you already have an account, run only **ONCE**
   ```bash
   npm run register
   ```
   * Enter your password
   * copy the token start with `eyJhbGciOiJIUzI1`
     
6. Create `tokens.txt` file
   ```
   nano tokens.txt
   ```
   * Paste your tokens start with `eyJhbGciOiJIUzI1`
   * Ctrl + O then enter to `save`
   * Ctrl + X to `exit`
  
7. Create Extension ID for `new account`
   ```bash
   npm run setup
   ```
   * save it and paste to `id.txt` file
   
8. Create `id.txt` file
   ```
   nano id.txt
   ```
     
9. Run the bot:
   ```bash
   npm run start
   ```

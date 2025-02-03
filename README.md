# Tea Fi Tx Bot

## Table Of Contents
- [Tea Fi Tx Bot](#tea-fi-tx-bot)
  - [Table Of Contents](#table-of-contents)
  - [Prerequisite](#prerequisite)
  - [Tea-Fi](#tea-fi)
  - [BOT FEATURE](#bot-feature)
  - [Setup \& Configure BOT](#setup--configure-bot)
    - [Linux](#linux)
    - [Windows](#windows)
  - [Update Bot](#update-bot)
  - [NOTE](#note)
  - [CONTRIBUTE](#contribute)
  - [SUPPORT](#support)

## Prerequisite
- Git
- Node JS
- Wallet Funded with POL on Polygon Mainnet

## Tea-Fi
#New 

Tea-FI Beta Test (RETRO) is Live
Reward pool 8.000.000 $TEA

Link : app.tea-fi.com/?ref=hpc347
- Open link & connect metamask ( new wallet )
- Deposit 1 POL ( MAINNET )
- Daily Swap POL > WPOL > tPOL no minimum
- Claim daily sugar
- Done

Nb :
At the end of the campaign, your Sugar Cubes will convert into Airdrop Rewards
Source : https://x.com/TeaFi_Official/status/1883152850374557883?t=PyiLO35Ntms_xYB_qsd_kA&s=19


## BOT FEATURE

- JUST GM


## Setup & Configure BOT

### Linux
1. clone project repo
   ```
   git clone https://github.com/Widiskel/tea-fi-bot.git 
   cd tea-fi-bot
   ```
2. run
   ```
   npm install
   npm run setup
   ```
3. Configure your accounts
   ```
   nano accounts/accounts.js
   ```
4. Configure your config
   ```
   nano config/config.js
   ```
5. to start the app run
   ```
   npm run start
   ```
   
### Windows
1. Open your `Command Prompt` or `Power Shell`.
2. Clone project repo
   ```
   git clone https://github.com/Widiskel/tea-fi-bot.git
   ```
   and cd to project dir
   ```
   cd tea-fi-bot
   ```
3. Run 
   ```
   npm install
   npm run setup
   ```
5. Navigate to `tea-fi-bot` directory. 
6. Navigate to `accounts` and configure `accounts.js`.
7. Navigate to `config` and configure `config.js`.
8. Back to `tea-fi-bot` directory. 
9. To start the app open your `Command Prompt` or `Power Shell` again and run
    ```
    npm run start
    ```

## Update Bot

To update bot follow this step :
1. run
   ```
   git pull
   ```
   or
   ```
   git pull --rebase
   ```
   if error run
   ```
   git stash && git pull
   ```
2. run
   ```
   npm update
   ```
2. start the bot

## NOTE
DWYOR & Always use a new wallet when running the bot, I am not responsible for any loss of assets.


## CONTRIBUTE

Feel free to fork and contribute adding or fixing some feature thanks. 

## SUPPORT

want to support me for creating another bot ?
**star** my repo or buy me a coffee on

EVM : `0x1f0ea6e0b3590e1ab6c12ea0a24d3d0d9bf7707d`

SOLANA : `3tE3Hs7P2wuRyVxyMD7JSf8JTAmEekdNsQWqAnayE1CN`

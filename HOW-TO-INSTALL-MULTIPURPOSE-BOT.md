![Logo](https://i.imgur.com/3sVP1xA.png)

# PixelMine | How to Install MultiPurpose Discord Bot

This document describes the installation of multi-purpose discord bot purchased by PixelMine customers. Everything is written in detail in the document. Please make sure that you have done everything for the installation. You can contact us about all the problems you are experiencing.

## Contact Us

- [Join Community](https://discord.gg/pixelmine)
- [Our Website](https://pixelmine.com)

## Supported OS & Technologies

- Windows/Linux/MacOS
- NodeJS
- Nodemon

There may be problems with hosting companies or ISP providers blocking API requests and some foreign connections. In this case, you can contact us.

### Dependencies;

The MultiPurpose bot requires different dependencies for different operating systems. Please make sure that all dependencies are installed for your operating system, otherwise the MultiPurpose bot may not start or work properly. Below are the dependencies that Corebot requires regardless of the operating system.

- 1: Node.JS v20.11.1+
- 2: Server (VPS, Windows, Linux, Bot Hosting or Your PC) (Min. 150MB Ram - 1 Core) 
- 3: Notepad++ - Visual Studio Code. (Recommend Visual Studio Code)
- 4: A connection to the internet.
- 5: ALL NPM Packages. (package.json)
- 6: MongoDB.

### Step 1: Create a your bot account;

- 1: Go to the Discord developer portal! [Click](https://discordapp.com/developers/applications)
- 2: Click the New application button.
- 3: Set the name of application then click Create button.
- 4: Select the Bot tab on the right side.
- 5: Click the Add bot button.
- 6: Confirm that would like to add a bot by clciking the "Yes, do it!" button.
- 7: Be sure to enable All of the Privileged Gateway Intents including "Presence Intent", "Server Member Intent" and "Message Content Intent". If you don't, the bot will not work properly.

### Step 2: Invite the bot to your server;

- 1: Select the OAuth2 tab then select the URL generator tab. 
- 2: Select the Bot and application.commands scopes and Administrator bot permission, then go to the link.
- 3: Choose your server and click the Authorize button.

### Step 3: Setup the multipurpose bot;

- 1: Join the src folder and open the config.json file. 
- 2: Add your license_code and support_code, server_id, bot_id and other informations.
- 3: The open the .env file in the main folder.
- 4: Add your bot_token, mongo_url and nvidia_api_key.

### Step 4: Start the multipurpose bot;

- 1: Once you have corrected all your information, you can use the start.bat or start.sh file.
- 2: To edit messages, you can edit them from /src/messageConfig.json.

Since the bot infrastructure and the whole system is still fresh, there may be errors. You can solve these errors by opening a ticket.

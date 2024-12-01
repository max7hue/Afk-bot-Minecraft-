# AterBot ✨  
[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](/LICENSE)  
### Keep your Aternos server alive 24/7.
Please star this project <3  
<br/>



# Important Notice 📢
### This project will be unmaintained until at least 2024.<br/>But you can use it as usual.



# Requirements 🎒
1. A Replit account.  
	Sign up at: https://replit.com/signup

2. An UptimeRobot account.  
	Sign up at: https://uptimerobot.com/signUp

3. A Minecraft server you owned.  
	Make sure your server settings ``online-mode`` set to ``false``!  
	And you should have an OP permission!



# Setup ⚙
1. Join your server.
2. Build a bedrock room somewhere, and stay in there.  
(Recommended room size: `X5 Y3 Z5`)
3. Go to [Replit](https://replit.com/).
4. Click `+` at the top right, click `Import from GitHub` at the close button.
5. Put `https://github.com/JadeMin/aterbot.git` into `GitHub URL`, click `Create Repl`.
6. Click `Run` at the top, your bot will join your server.  
7. **Teleport the bot into the bedrock room, change the bot's gamemode to `Creative` to not die!**
8. You'll see the `Webview` tab on Repl, copy the url.
10. Go to [UptimeRobot](https://uptimerobot.com/dashboard).
11. Click `Add New Monitor`, select `Monitor Type` to `HTTP(s)`.
12. Paste the url copied in `Step 8` into `URL (or IP)`.
13. Click `Create Monitor` 2 times.

Finally... DONE! Enjoy your free 24/7 Aternos server.


#Edit the config.json

```javascript
{
	"client": {
		"host": "YOR_IP_OD_YOUR_SERVER",
		"port": "YOUR_PORT_OF_YUR_SERVER_HERE",
		"username": "Kazuto_BoT7"//Change the user name of the bor make sure has "_"
	},
	
	"! DO NOT EDIT BELOW !": "ONLY IF YOU KNOW WHAT YOU ARE DOING",
	"logLevel": ["error", "log", "debug"],
	"action": {
		"commands": ["forward", "back", "left", "right", "jump"],
		"holdDuration": 5000,
		"retryDelay": 15000
	}
}
```
# Run it on Render
build comamnd;
```javascript
yarn
```
start comamnd;
```javascript
pnpm run start
```

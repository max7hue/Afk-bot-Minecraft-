# Created by Aljur Pogoy




# AterBot ✨  
[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](/LICENSE)  
### Keep your Aternos server alive 24/7.
Please star this project <3  
<br/>



# Important Notice 📢
### This project will be unmaintained until at least 2024.<br/>But you can use it as usual.



# Requirements 🎒
1. A render account.  
	Sign up at: dashboard.render.com

2. An UptimeRobot account.  
	Sign up at: https://uptimerobot.com/signUp

3. A Minecraft server you owned.  
	Make sure your server settings ``online-mode`` set to ``false``!  
	And you should have an OP permission!


# Edit the config.json

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

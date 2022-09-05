# ClubPenguinClient

This club penguin client is a "flash port" for people like me that want a private server

# Download client / Descargar cliente

**WARNING: For people that are searching the build of my client for my private server please DO NOT keep reading this guide**

# Config file

The config file has various things that you need to change

**If you want to change something please go to the file [config.json](./config.json)**

```json
{
	"mainURL": "Your url of your private server",
	"repositoryName": "The name of your repo in github",
	"discordRpc": {
		"enable": true, // This setting its if you want to enable the discord presence
		"discordAppId": "The ID of your presence app",
		"activityTitle": "The activity title",
		"activityDescription": "The activity description",
		"buttons": [
			{
				"label": "Button",
				"url": "https://www.juizzi.fi"
			}
		] //This are buttons, you can configure them
	},
	"windowSettings": {
		"width": 1280,
		"height": 720
	} //These are settings of the window, please do not change this
}
```

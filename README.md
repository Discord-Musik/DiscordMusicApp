# DiscordMusicApp
## Setup
The setup here is fairly easy, you will be using your own computer to serve the application when you intend to use the service. 
The first step is to clone the repository, then navigate to the directory that you had preveously cloned the app.

You can decide how to handle envrinment variables but I just keep a local `config.json` file in the apps root directory and add it to .gitignore.\
That config.json can be configured as such: 

```
{
   "clientId": "your client Id (discord)",
   "prefix": "Prefix of your choozing (i.e. /, pls, +)",
   "token": "Your token (discord)"
}
```

You get these credentials by navigating to the [Discord developer portal](https://discord.com/developers/applications) and finding/creating your bot.

---

Then simply install you local deps by running `npm install` 

Once that's finished then you can run your local dev server by using `npm run start`

## Notes
This application was written with the latest version of Discord.js (v13), if you'd like to expand on the project be warry, as there are a lot of differences between v12 and v13. This took a lot longer than expected as documentation is slim...
You can view the Docs for Discord.js [here](https://discord.js.org/#/docs/main/stable/general/welcome).

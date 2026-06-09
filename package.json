const { Client } = require('discord.js-selfbot-v13');
const client = new Client({ checkUpdate: false });

client.on('ready', () => {
  console.log(`Logged in as ${client.user.tag}!`);
  
  client.user.setPresence({
    activities: [{
      name: "Kirriya Universe", 
      type: "STREAMING",
      url: "https://www.twitch.tv/rex" 
    }],
    status: "online"
  });
});

client.login(process.env.DISCORD_TOKEN);

const Discord = require("discord.js");
const client = new Discord.Client();

client.on('ready', () => {
  console.log(`Logged in as ${client.user.username}!`);
});

client.on('message', msg => {
  if (msg.content === 'ping') {
    msg.reply('Pong!');
  }
});

client.login('NDE2MzEzMDUzMjk0ODg2OTIy.DXHElw.g9OvvIQF0rODCvY0cxsSL0mOaJQ');

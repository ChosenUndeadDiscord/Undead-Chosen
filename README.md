const Discord = require("discord.js");
const client = new Discord.Client();

client.on('ready', () => {
  console.log(`Logged in as ${client.user.Undead Chosen}!`);
});

client.on('message', msg => {
  if (msg.content === 'ping') {
    msg.reply('Pong!');
  }
});

client.login('NDE2MzEzMDUzMjk0ODg2OTIy.DXG4Bw.FAblGhe7RXyYXn1doGbO62YB9OQ');

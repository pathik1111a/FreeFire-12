const Discord = require('discord.js');

const client = new Discord.Client();

client.on('ready', () => {

  console.log(`Logged in as ${628185197187301378}!`);

});

client.on('message', msg => {

  if (msg.content === 'ping') {

    msg.reply('Pong!');

  }

});

client.login(803197908953464852)

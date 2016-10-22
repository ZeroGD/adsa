var Discord = require('discord.io');
var bot = new Discord.Client({
    token: "MjM5NDk4NDI0NDY1MDk2NzA1.Cu1pzg.0eETMTz4v9UOUVh2sXmiZv5JHog",
    autorun: true
});

bot.on('ready', function() {
    console.log(bot.username + " - (" + bot.id + ")");
});

bot.on('message', function(user, userID, channelID, message, event) {
    if (message === "kys scum of the earth") {
        bot.sendMessage({
            to: channelID,
            message: "message"
        });
    }
});

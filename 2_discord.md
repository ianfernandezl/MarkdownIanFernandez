# Documentació del Bot de Discord

![Logotip de Discord](https://img.magnific.com/vector-premium/logotipo-redes-sociales-vector-discord_534308-21667.jpg?semt=ais_hybrid&w=740&q=80)

Pots registrar la teva aplicació al [Portal de Desenvolupadors de Discord.](https://discord.com/developers/applications)

Per fer que el bot respongui, escoltem l'esdeveniment messageCreate i utilitzem el mètode message.reply()" (utilitzant el format de codi per a messageCreate i message.reply())

```Java
client.on('messageCreate', message => { 
    if (message.content === 'ping') { 
        message.reply('pong!'); 
    } 
});
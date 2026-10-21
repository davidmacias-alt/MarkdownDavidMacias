# Documentació del Bot de Discord #
 
<img src="https://upload.wikimedia.org/wikipedia/fr/4/4f/Discord_Logo_sans_texte.svg" alt="Logotip de Discord" width="400">

Pots registrar la teva aplicació al [Portal de Desenvolupadors de Discord](https://discord.com/developers/applications).
 
Per fer que el bot respongui, escoltem l'esdeveniment messageCreate i utilitzem el mètode message.reply().
 
```javascript
client.on('messageCreate', message => {
  if (message.content === 'ping') {
    message.reply('pong!');
  }
});
```
```
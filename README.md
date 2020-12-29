# Welcome 
This is official version of asos language
## Installion
```$ npm i asos-new```
## Start
Create a file name ```index.js```, now, use this code:
```js
const Asos = require('asos-new')
const client = new Asos.Client();

client.on('message', msg => {
    if (msg.content === 'ping') {
      msg.reply('pong');
    }
  });

client.login('your bot token')
```
Now, using this command to switch on the bot:
``` $ node . ```
Congratulation, you made a bot!!!

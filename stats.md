# TheHosting Bot
Le Bot qui relie votre installation Pterodactyl et WHMCS directement à Discord. Vous offrant une facilité d'utilisation de vos serveurs.

<p align="center">
  <img width="250" src="https://thehostingbot.xyz/logo.png">
</p>

## Utiliser l'api statistiques

```javascript
const axios = require("axios");
axios
  .get('https://api.thehostingbot.xyz/stats.json')
  .then(response => {
  console.log(response.data)
  })
  
/*exemple de réponse dans la console : 
{
  "bot": {
    "users": 38,
    "servers": 7,
    "ping": 115,
    "vDJS": "12.3.1",
    "vNJS": "v12.4.0"
  },
  "clients": { "total": 4, "free": "-", "satisfaits": "-", "files": "-" },
  "lastupdate": "15 novembre 2020 14:49"
}*/
```


• [Site Web](https://thehostingbot.xyz/)

• [Espace Client](https://manager.thehostingbot.xyz/)

• [Guide](https://guide.thehostingbot.xyz/)

• [Ajouter le bot](https://thehostingbot.xyz/inviter)

• [Rejoindre le serveur Discord](https://thehostingbot.xyz/discord)


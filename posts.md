# TheHosting Bot
Le Bot qui relie votre installation Pterodactyl et WHMCS directement à Discord. Vous offrant une facilité d'utilisation de vos serveurs.

<p align="center">
  <img width="250" src="https://thehostingbot.xyz/assets/images/image022569.png?v51105510535061">
</p>

## Utiliser l'api posts

```javascript
const axios = require("axios");
axios
  .get('https://manager.thehostingbot.xyz/api/posts')
  .then(response => {
  console.log(response.data)
  })
  
/*exemple de réponse dans la console : 

  {
    "id": 5,
    "title": "[Client Spotlight] NetHeberg.fr !",
    "description": "NetHeberg est client de TheHosting Bot ! D\u00e9couvrez \u00e0 travers le programme Client Spotlight NetHeberg.fr !",
    "slug": "spotlight-netheberg",
    "url": "https://manager.thehostingbot.xyz/news/spotlight-netheberg",
    "content": "<p><strong>Qu'est-ce que NetHeberg ?</strong></p>\r\n<p>\ud83d\udc49 \u00a0Un h\u00e9bergement web gratuit et complet fond\u00e9 par Antoine Jouary<br />\ud83d\udc49\u00a0 Un h\u00e9bergement web fiable et transparent</p>\r\n<p><strong>Offres web sont disponible :</strong></p>\r\n<p>\ud83d\udce7 - Adresse mail illimit\u00e9s<br />\ud83d\udd29 - Comptes FTP illimit\u00e9s<br />\ud83d\udce5 - 500mo/1Go ou m\u00eame 10Go(offres professionnelles) de stockage<br />\ud83d\udce8 - Trafic de donn\u00e9es illimit\u00e9<br />\ud83d\udcdf - Sous domaines illimit\u00e9s<br />\ud83d\udcbb - Un plesk et cpanel tr\u00e8s complet pour g\u00e9rer tout \u00e7a !<br />\u26a1 - Un nom de domaine gratuit en .netheberg.fr* ou .nhx.fr* ou .xnh.fr* ou .monpanel.info*\u00a0 ou m\u00eame votre propre domaine qu'il soit gratuit ou pay\u00e9.<br /><span style=\"text-decoration: underline;\">D'autres offres sont disponibles sur le site</span></p>\r\n<p><br /><span style=\"text-decoration: underline;\">Pourquoi choisir NetHeberg ?</span></p>\r\n<p>\u27a1\ufe0f NetHeberg est un n\u00e9o-h\u00e9bergeur fran\u00e7ais gratuit, complet, avec une indexation Google pour la plupart des sites h\u00e9berg\u00e9s et meilleur que la plupart des h\u00e9bergeurs gratuits actuels avec un support rapide et efficace et sa disponibilit\u00e9 incroyable.\u00a0</p>\r\n<p><strong>N'attends pas, rejoins Netheberg !</strong></p>\r\n<p>\ud83d\udcdc - <a href=\"https://discord.gg/wh3aTY7\" target=\"_blank\" rel=\"noopener\">Le discord</a><br />\ud83d\udd17 - <a href=\"https://netheberg.fr\" target=\"_blank\" rel=\"noopener\">Le site web</a></p>\r\n<p>A bient\u00f4t sur Netheberg \ud83d\ude09<br /><br /><em>* sous domaine d\u00e9pendant de l'offre choisie</em></p>",
    "author": {
      "id": 5,
      "name": "Partenaires",
      "role": { "id": 2, "name": "Administrateur", "color": "#e10d11" },
      "registered_at": "2020-11-15T17:37:11+01:00"
    },
    "published_at": "2020-11-15T17:37:54+01:00",
    "image": "https://manager.thehostingbot.xyz/storage/posts/SX8qh1BqAfJr61AHYPUcFGMRLYNR6SnQzLFW9cir.jpeg"
  },
  {
    "id": 4,
    "title": "Lancement du projet !",
    "description": "D\u00e9couvrez d\u00e8s maintenant TheHosting Bot !",
    "slug": "ouverture-du-projet-beta",
    "url": "https://manager.thehostingbot.xyz/news/ouverture-du-projet-beta",
    "content": "<p>Bienvenue \u00e0 vous g\u00e9rant d'h\u00e9bergeur !<br /><br />D\u00e9couvrez nos services pour votre installation WHMCS et Pterodactyl. Facilitez vous la vie, TheHosting Bot g\u00e8re pour vous !<br /><br />Testez gratuitement TheHosting Bot avec l'offre gratuite limit\u00e9e \u00e0 un utilisateur pour Pterodactyl et un administrateur pour WHMCS.<br /><br /><strong>Vous Souhaitez devenir B\u00eata-Testeur ?</strong></p>\r\n<p>Nous appr\u00e9cions votre enthousiasme ! Testez nos produits en version d'essai et envoyez nous vos suggestions et am\u00e9liorations que vous souhaiteriez avoir sur le service propos\u00e9. <br /><br />Les B\u00eata-Testeurs les plus productifs peuvent recevoir 1 ou deux mois gratuit(s) de licence cumul\u00e9e !<br /><br />Qu'attendez vous ?<br /><br /></p>\r\n<ul>\r\n<li><a title=\"Ajoutez TheHosting Bot et profitez de la version gratuite !\" href=\"https://thehostingbot.xyz/inviter\" target=\"_blank\" rel=\"noopener\">Ajoutez TheHosting Bot et profitez de la version gratuite !</a></li>\r\n<li><a title=\"Rejoignez notre Discord et commencez \u00e0 discuter avec les d\u00e9veloppeurs !\" href=\"https://thehostingbot.xyz/discord\" target=\"_blank\" rel=\"noopener\">Rejoignez notre Discord et commencez \u00e0 discuter avec les d\u00e9veloppeurs !</a></li>\r\n</ul>",
    "author": {
      "id": 4,
      "name": "Jean_S",
      "role": { "id": 2, "name": "Administrateur", "color": "#e10d11" },
      "registered_at": "2020-11-15T17:18:32+01:00"
    },
    "published_at": "2020-11-15T17:20:43+01:00",
    "image": "https://manager.thehostingbot.xyz/storage/posts/GCQvkmDJ5y9ut9GCoErfR5qHtyv4c8pt0TbA13Yj.png"
  }
]*/
```


• [Site Web](https://thehostingbot.xyz/)

• [Espace Client](https://manager.thehostingbot.xyz/)

• [Guide](https://guide.thehostingbot.xyz/)

• [Ajouter le bot](https://thehostingbot.xyz/inviter)

• [Rejoindre le serveur Discord](https://thehostingbot.xyz/discord)


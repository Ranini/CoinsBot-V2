
# :robot: **CoinsBot V2 remade by ruwinou**

## **Description**
T'as toujours réver d'avoir un système d'économie sur ton serveur mais t'as pas les moyens ? Voici le bot qui va te servir, avec un système de coins, de team, de métiers et bien plus encore !

## **Fonctionnalités**
- système d'économie

## **Configuration**

### **Prérequis**
- Discord.js (version 14.11.0)
- mysql (version 2.18.1)
- phpMyAdmin (voir étape instalation)

### **Étapes d'installation**
1. Clone le repository : `git clone https://github.com/ton-repository.git`
2. Installe les dépendances : `npm install`
3. Utilise phpMyAdmin et met le fichier `coinsbot.sql` dessus si tu n'as pas phpMyAdmin ou que tu ne sais pas l'utiliser je t'invite à te rendre dans le serveur https://discord.gg/cloudhive et demander un hébergeur avec phpMyAdmin pour le coinsBot (de la part de ruwinou) C'EST TOTALEMENT GRATUIT !!! Toutefois si t'as d'autre problème je t'invite à te rendre dans le serveur https://discord.gg/whitehall
4. Configure ton fichier de configuration `config.json` avec les informations nécessaires.
5. Lance le bot : `node index.js`

### **Configuration du fichier `config.json`**
```json
{
  "token": "TON_TOKEN_BOT",
  "prefix": "TON_PREFIXE",
  "ownerId": "ID_DU_BUYER",

  "linkbot": "Lien_du_bot",
  "BDD": {
        "host": "HOST",
        "port": "PORT",
        "user": "USER",
        "database": "coinsbot",
        "charset": "utf8mb4"
    }
  
}
```

## **Contribution**
Si tu souhaites contribuer à ce projet, n'hésite pas à ouvrir une pull request !

## **License**
Ce projet est sous license Apache. Voir le fichier `LICENSE` pour plus d'informations.

## **Support**
Serveur Discord: https://discord.gg/xkebY6nsxk
Message Privé: ruwinou




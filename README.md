# DM de masse

![image](https://cdn.discordapp.com/attachments/1095992593252368384/1096554378166534384/image.png)

**Description :** Outil qui envoie des messages à tout le monde sur un serveur Discord (si l'utilisateur a désactivé les DM, il ne peut pas recevoir de message).

**Caractéristiques:**

- 2 nouveaux modes DM ('Normal' et 'Timeout').
- Contourner/éviter les drapeaux de spam de Discord.

- Mode normal:
  - Vitesse DM : Tentatives de dm en moins d'une seconde entre chaque utilisateur.
- Mode temporisé :
  - Vitesse DM : 3 à 9 secondes de délai d'attente entre chaque DM.
  - Risque de signalement du bot : très faible.

Doit avoir [Node.JS LTS Version](https://nodejs.org/en/) installé et une sorte d'éditeur de texte.
Mettez votre jeton de bot dans le `settings.json`.

**Exemple : jeton**
```
{
    "jeton": "NzYzNjM5ODE2Mzg1JKaykuk.X36o_w.LkrJSMHlUIpj_p93Xo9agfEg50k"
}
```

**Exemple : message**
```
{
    "jeton": "NzYzNjM5ODE2Mzg1JKaykuk.X36o_w.LkrJSMHlUIpj_p93Xo9agfEg50k",
    "message": "Test\nTest\n\ntest"
}
```

**Résultat:**

![Résultat](https://media.discordapp.net/attachments/790498161533517835/864837793510064138/unknown.png)

**Installation:**
1. Exécutez le fichier `Launch.bat` pour installer les modules requis.
2. Exécutez le fichier `run.bat` pour démarrer le programme.

**Remarque :** Toutes les intentions de vos bots doivent être activées. Comment faire ? `Dev Portal > Bot > Privileged Gateway Intents` **(activez les deux intentions)**

**Autorisation requise :** "Administrateur".

## Clause de non-responsabilité:
Cet outil a été conçu à des fins éducatives et de preuve de concepts. Je ne suis pas responsable de toute action illégale et sans précédent et de toute violation des conditions d'utilisation administrées par un tiers.

Si le mode normal a été utilisé, votre bot sera signalé par Discord. Comment résoudre ce problème :
   - Allez appeler pour un [appel](https://support.discord.com/hc/en-us/requests/new?ticket_form_id=360000029731) et sélectionnez "Appeal an Action Trust and Safety take on my bot" comme rapport Tapez pour votre bot afin que le bot ne soit plus signalé.
   - Créez simplement un nouveau bot.

Les bots non vérifiés ne peuvent pas Masser les serveurs DM de plus de 1 000 membres. Assurez-vous que votre bot est vérifié si vous essayez de Masser des serveurs DM de plus de 1 000 membres.

## Contactez moi

﹒[Discorde](https://discord.com/users/923619890873643041)
 

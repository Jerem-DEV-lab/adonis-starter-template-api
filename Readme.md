# **Description du projet**
Template de démarrage rapide pour un projet adonis-js avec les packages déjà installer et préconfigurer comme : 
- [@adonisjs/auth](https://docs.adonisjs.com/guides/auth/introduction)
- [@adonisjs/lucid](https://docs.adonisjs.com/guides/database/introduction)

# **Configuration du projet**

- Étape 1 : Installer les dépendences `pnpm i`
- Étape 2 : Créer le fichier `.env` à la racine du projet (vous pouvez vous référer au fichier `.env.example`)
- Étape 3 : Configurer vos variables d'environnements qui se situent dans le fichier `.env` que vous venez de créer
- Étape 4 : Modifier la migration qui a été prêt créer.
- Étape 5 : Modifier le model User
- Étape 6 : Lancez les migrations en entrant dans votre terminal ``node ace migration:run``

Pour l'authentification, vous devrez au préalable installer une dépendences pour le cryptage du mot de passe : 
Exemple : ``pnpm add phc-argon2``

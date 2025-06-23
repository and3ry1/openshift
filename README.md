# Exercice Openshift #1 - Déploiement d'une API Node.js

Via Opennshift, réaliser le déploiement de l'application [ci-jointe](./app-v1.zip).

Cette application est une API en Node.js fonctionnant via le module Express.js

* L'API écoutera à la variable d'environnement PORT (ou à 3000 par défaut). 
* Elle possède un unique endpoint: `GET /` qui doit retourner le message **Hello World!**

Vous devrez donc la déploier dans le cluster Openshift. Pour cela, vous avez le choix entre réaliser un déploiement via l'image ou via le code source (idéalement, faites les deux pour pratiquer).

Pour lancer l'application localement, il suffit d'avoir node.js d'installé et de faire les lignes de commandes suivantes: 

```bash
npm install # Pour installer les dépendances

npm start # Pour démarrer l'API
```
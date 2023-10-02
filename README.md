# Mudey Create Express

Un utilitaire en ligne de commande pour générer rapidement des projets Express.js avec TypeScript.

## Installation

Assurez-vous d'avoir Node.js installé sur votre système.

Pour installer l'utilitaire `mudey-create-express`, vous pouvez utiliser `npm` (le gestionnaire de paquets Node.js) en exécutant la commande suivante :

```bash
npm install -g mudey-create-express
```

## Utilisation

Après avoir installé l'utilitaire, vous pouvez le lancer depuis votre terminal avec la commande suivante :

```bash
mudey-create-express <nom-du-projet>
```

Par exemple, pour créer un projet Express.js avec TypeScript nommé "mon-projet-express", vous pouvez exécuter :

```bash
mudey-create-express mon-projet-express
```

Cela créera un répertoire "mon-projet-express" contenant une application Express.js de base avec TypeScript, prête à l'emploi.

## Structure du Projet

Le projet généré par `mudey-create-express` aura la structure suivante :

- `/config`: Contient les fichiers de configuration.
- `/public`: Contient les fichiers statiques (images, CSS, JavaScript, etc.).
- `/src`: Contient le code source de l'application.
  - `/controllers`: Contient les contrôleurs de l'application.
  - `/models`: Contient les modèles de données.
  - `/routes`: Contient les fichiers de routage.
  - `/views`: Contient les fichiers de vue (templates).
- `/storage`: Contient les fichiers de stockage (uploads, fichiers temporaires, etc.).

## Démarrage

Pour démarrer votre projet, suivez ces étapes :

1. Accédez au répertoire du projet :

   ```bash
   cd mon-projet-express
   ```

2. Installez les dépendances du projet en exécutant :

   ```bash
   npm install
   ```

3. Lancez l'application avec la commande :

   ```bash
   npm start
   ```

Votre application Express.js avec TypeScript démarrera sur le port par défaut 3000. Vous pouvez accéder à l'application dans votre navigateur en visitant `http://localhost:3000`.

## Personnalisation

Vous pouvez personnaliser davantage votre application Express.js en modifiant le code dans le répertoire `/src`. Vous pouvez ajouter des routes, des contrôleurs, des modèles, des vues, etc., selon vos besoins.


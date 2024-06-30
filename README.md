# version

Pour changer la version de votre ressource sur FiveM, suivez ces étapes :

1. **Rendez-vous sur le site de Keymaster :**
   Accédez à [Keymaster](https://keymaster.fivem.net/) en utilisant votre navigateur.

2. **Accédez à "Granted Assets" :**
   Une fois connecté, allez dans la section "Granted Assets" pour voir toutes les ressources que vous avez autorisées.

3. **Trouvez la voiture dont la version doit être changée :**
   Recherchez la ressource spécifique (dans ce cas, une voiture) qui nécessite une mise à jour.

4. **Téléchargez la nouvelle version :**
   Téléchargez la nouvelle version de la ressource depuis le site.

5. **Mettez la nouvelle version sur votre serveur :**
   Remplacez les fichiers de l’ancienne version de la ressource par ceux de la nouvelle version sur votre serveur.

6. **Assurez-vous d’activer la ressource :**
   Utilisez la commande `ensure` pour activer la nouvelle version de la ressource dans votre configuration de serveur.

Voici un exemple de commande pour activer la ressource dans le fichier `server.cfg` :

```
ensure nom_de_la_ressource
```

Remplacez `nom_de_la_ressource` par le nom de la ressource que vous avez mise à jour. 

Après avoir suivi ces étapes, redémarrez votre serveur pour que les modifications prennent effet.

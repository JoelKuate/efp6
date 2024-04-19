

1. Copiez l'URL du dépôt GitHub que vous souhaitez cloner.
2. Ouvrez votre terminal ou votre interface de ligne de commande.
3. Utilisez la commande `git clone <URL>` en remplaçant `<URL>` par l'URL que vous avez copiée. Par exemple :
   ```
   git clone https://github.com/nom_utilisateur/nom_projet.git
   ```
4. Accédez au répertoire du projet cloné en utilisant la commande `cd nom_projet`.
5. Effectuez les modifications nécessaires dans les fichiers du projet à l'aide de votre éditeur de texte ou de votre environnement de développement préféré.
6. Une fois que vous avez apporté vos modifications, utilisez la commande `git add .` pour ajouter tous les fichiers modifiés à l'index.
7. Ensuite, utilisez la commande `git commit -m "Message de commit"` pour valider vos modifications avec un message descriptif.
8. Si vous n'avez pas déjà un dépôt distant configuré, vous pouvez l'ajouter en utilisant la commande `git remote add origin <URL>`, en remplaçant `<URL>` par l'URL de votre nouveau dépôt GitHub.
9. Enfin, utilisez la commande `git push -u origin master` pour pousser votre projet vers le nouveau dépôt distant que vous venez de créer sur GitHub.


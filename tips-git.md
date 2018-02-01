# Tips Git

## Si ssh ne marche pas, contraindre à passer en https
ajouter dans le fichier config dans .git

```
[url "https://"]
    insteadOf = git://
```

Pratique quand tu dois faire un `npm install` et que tous les paquets sont référencés en ssh… tu va pas changer tous les fichiers à la main…
Merci @borisschapira


# Formation React 2025

## Exercice 1

### Initialisation d'un nouveau projet React
- Lancer la commande ```npx create-react-app exercice_1```
- Dans le dossier ```exercice_1``` lancer les commande ```npm install``` (ou ```npm i```) puis ```npm start```

### Création d'un premier composant React
- Dans le package ```./src/components/exercice-1```. créer le composant ```Exercice1``` dont le comportement est le suivant :
  - Le composant affiche un header avec le titre « Exercice 1 »
  -	Le composant affiche en contenu « Hello world ! »
  -	Le composant affiche un footer avec la date et l’heure

- Dans le fichier ```./src/App.js``` supprimer le code retourné et appeler le composant.

 
Note : on pourra utiliser la fonction javascript ```toLocalDateString``` de ```Date``` pour afficher la date et l’heure au format voulu (voir [Date.prototype.toLocaleString()](https://developer.mozilla.org/fr/docs/Web/JavaScript/Reference/Global_Objects/Date/toLocaleDateString)).

<u>Exemple :</u>
```
new Date().toLocaleDateString('fr-FR', {
    weekday: 'long',
    year: 'numeric',
    month: 'long',
    day: 'numeric',
    hour: 'numeric',
    minute: 'numeric',
    second: 'numeric',
})
```
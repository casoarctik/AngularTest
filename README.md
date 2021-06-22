# Interrogation Angular

Une fois votre devoir terminer, envoyer le moi par mail à l'adresse : ange.picard@pm.me.

**PENSEZ BIEN A SUPRRIMER LE DOSSIER .git ET node_modules**

> Pas la peine de faire de CSS, uniquement l'aspect fonctionnel sera pris en compte.

## Informations

Nom: BEAUMONT
Prenom: Colin

## Question ouvertes

Merci de répondre avec vos mots, même s'ils sont inexactes, je veux voir que vous avez compris, pas que vous savez faire un copier-coller.

### Qu'est qu'Angular et quel est son intérêt ?

```
Angular est un framework MVC TypeScript (amélioration JavaScript) créé par Google, il est utilisé pour les applications web 
```

### Qu'est-ce-qu'un composant

```
C'est une classe qui permet de découper sa page web plus facilement, la page en elle même est un composant, elle peut acceuilir plusieurs autres petits composant comme une barre de navigation, un bloc de contenu principale, une sidebar...chaque composant est ensuite représenté dans du html par une balise personalisée qui permet d'être dupliqué ou placé ou l'on souhaite
```

### Comment est découper un composant dans Angular ?

```
C'est une classe disposant d'attributs, de fonctions, de constructeurs parfois ainsi que 2 templates HTML et CSS. 
```

### Pourquoi vaut-il mieux faire de petit composant ?

```
Pour eviter de faire des composants trop généraux, plus difficile à modifier. De même que si l'on code tout sur le composant de la page (le principal) on perd l'interet d'angular et la faculté d'utiliser les balises personalisées pour organiser son HTML facilement et proprement.
```

### A quoi sert un service ?

```
Il permet de récupérer des données ou d'échanger entre les composants pour qu'ils communiquent entre eux.
```

### Qu'est-ce-qu'un observable, et quel est son intérêt ?

```
C'est un Objet qui permet de traiter efficacement les données, il peut analyser, modifier et maintenir les données dans un système basé sur les événements.
```

## Exercice 1

- Créer un nouveau projet Angular
- Dans le AppComponent
    - Ajouter un input
    - Ajouter un span
    - Faire en sorte que quand l'utilisateur entre du contenu dans l'input, il soit également écrit dans le span. On voit la même chose dans le span et dans l'input.
    - Ajouter un bouton permettant de vider le contenu de l'input et du span
- Créer un composant ListComponent
    - L'ajouter dans le template du AppComponent
    - Afficher la liste qui suit dans ListComponent
        - ['Jean', 'Jacques', 'Martin']
- Ajouter un bouton "CACHER" dans le AppComponent
    - A chaque click, cacher ou afficher ListComponent

## Exercice 2

Cette partie de l'interrogation porte sur le projet PokeAdopt.

Pour l'instant l'application n'affiche que la première page de la liste de pokemon l'API.

- Ajouter un bouton précédent et suivant en haut de la liste
- Quand on clique sur précédent ou suivant, afficher la page précédente ou suivante de l'API
- Bonus: Griser le bouton précédent s'il n'y a pas de page précédente
- Bonus: Afficher le numéro de page entre les deux boutons (Page 1 / XXX)

# Post
Une application d'article, pour lister les articles

## Dépendences
- [NodeJS](https://nodejs.org/en/)
- [npm](https://nodejs.org/en/)
- [Angular.io](http://angular.io)

## Installation
```console
git clone http://github.com/ognanshissi/frontend-test-post-app post-app
cd post-app
npm i
```

## A Savoir
**Endpoints**

Pour la liste des articles: [https://jsonplaceholder.typicode.com/posts](https://jsonplaceholder.typicode.com/posts)

Liste des commentaires: [https://jsonplaceholder.typicode.com/comments](https://jsonplaceholder.typicode.com/comments)


## A Faire
- Lister les posts en `lazy loading`, 10 en premier et a chaque qu'on clique sur `Lire la suite` charger les 10 suivant
- Cacher le bouton `Lire la suite` lorsque tout les articles sont affichés
- Retourner uniquement les propriétés `id, title` 
- Transformer les titre en `TitleCase`

# My Events

## Listing d'événements et de sorties culturelles (concert, expo...)

## Introduction

\*_Projet d'école réalisé au sein de la W@C_

Utilisation de l'API d'Opendatasoft.

- MongoDB
- Express.js
- React
- Node.js

## Usage

```bash
cd client && npm install;
cd server && npm install;
cd..

sudo mongod -f mongodb.conf # (tcp/27042)

cd client &&
npm start ;

node ./server/index.js 127.0.0.1:5000 ;

firefox http://localhost:3000/
```

## Cahier des charges

### Gestion des utilisateurs

- Un système de connexion : l’utilisateur peut se connecter en fournissant un nom d’utilisateur.
- Un système d'inscription : l’utilisateur peut s'inscrire

### Filtres

- Possibilité de filter les événements et de faire une recherche par mots-clés / texte

<img src="my_events.gif" height="350px" style="margin: 1em; border-radius:.25em;" alt="demo">

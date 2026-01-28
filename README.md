# les astuces à connaitre pour ce project backend

- [ les commandes à savoir pour lancer l'application ]
```bash
  #  la ligne de commande pour lancer l'appli
  $ npm run start

  #  la ligne de commande pour lancer l'appli en mode watch
  $ npm run start:dev

```


- [ les commandes à savoir pour prisma ]
```bash

  # pour voir les données à tavers le navigateur
  $ npx prisma studio

  # la commande après avoir changer la structude d'un tableau dela base de données
  $ npx prisma generate

  # la commande pour aprèes qu'une autre personne aie ajouté une table dans la base des bonnées
  $ npx prisma db pull

  #  la commande qu'une personne doit lancer pour envoyer une table à la base de données et voir  le model de la table crée dans voir environement de developpement
  $ npx prisma migrate dev --name " le msg que vous voulez dire concernant le tableau"
  
  # #  la commande qu'une personne doit lancer pour envoyer une table à la base de données et voir  le model de la table crée dans voir environement de developpement
  $ npx prisma db push 

```

- [ les manières de créer la table ]
```js
  model User {
    id String @id @default(uuid())
    lastname String 
    isSubscribed Boolean @default(false)
    isProgrammer Boolean @default(false)
    age Int 
  }
```

# les choses essentielles à n'est pas oublier 
- [ npm install : après avoir cloner le project ]
```bash
  $ npm install
```

- [ npx prisma generate ]
```bash
  $ npx prisma generate 
```

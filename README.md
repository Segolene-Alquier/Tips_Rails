# Petite fiche à garder sous la main

## Revenir en arrière sur Rails

_**Supprimer un controller**_

```$ rails destroy controller Xxx```

_**Supprimer un model**_

```$ rails destroy model Xxxx```

_**Supprimer une migration**_

```$ rails db:rollback```

_**Supprimer toutes les migrations**_

```$ rails db:migrate VERSION=0```
> il est possible de remplacer le 0 par n'importe quel autre chiffre correspondant à une migration

## Les opérations GET, POST, PATCH and DELETE

HTTP (hypertext transfer protocol) définit les opérations GET, POST, PATCH, and DELETE. 
> elles réfèrent à des opération entre un client (généralement un navigateur) et un serveur.

* GET est l'opération HTTP la plus commune : permet de lire des données sur le web. Ça signifie “get a page”, et chaque fois que l'on visite un site comme http://www.google.com/ le navigateur envoie une requête GET. 
* POST est la 2ème opération la plus commune : c'est la requête envoyée par le navigateur lorsqu'on soumet un formulaire. Sur Rails, elle est utilisée pour créer des objets
* PATCH : permet de modifier des données sur un serveur distant
* DELETE : permet de supprimer des données sur un serveur distant





RAJOUTER SUR LES MAJUSCULES ET SINGULIERS ET PLURIEL


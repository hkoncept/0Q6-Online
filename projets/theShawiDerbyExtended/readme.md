
<h1 align="Center">🏇 The Shawi Derby Extended 🏇</h1>
<h2 align="Center">Présenté par 🕹️GameZone Inc.</h2>
<p align="Center"><img src="./images/derby.png" alt="drawing" width="550"/></p>

## Introduction

Vous avez présenté votre application de Derby à votre client, l'entreprise 🕹️GameZone Inc., et ils sont vraiment satisfait de votre travail. Ils souhaitent continuer avec vous pour améliorer le projet que son employé Cédrik à débuté en se basant sur votre oeuvre. 🕹️GameZone Inc. demande maintenant de :

1. Partir une nouvelle solution/projet explicitement nommé `ShawiDerbyExtended` avec le [code de Cédrik](./_bin/TP3-ShawiDerbyExtended.txt) en ne modifiant rien de ce qui est déjà présent mais en utilisant tout le code présent.
2. Lire les données de chevaux et de derbies depuis une [base de donnée CSV](./_bin/data.zip).
3. Enregistrer les données dans des structures nommées `Derby` et `Horse`.
   1. `Horse` : Structure pour un cheval de course incluant les fonctions `toString()` retournant les infos du cheval et `run()` servant à faire avancer d'un nombre de pas aléatoire contenu entre `MIN_STEPS` et `MAX_STEPS`.
   2. `Derby` : Structure pour les information du Derby incluant, entre autres, la longueur en km de la piste de course et un tableau des chevaux.  Cette structure aura également une fonction `toString()` permettant d'afficher ses propres info et une fonction `getWinner()` qui retourne la ligne de course gagnante (0 à 9).  Prennez bien soin de comprendre, avec la vidéo, la différence entre un # de ligne de course et un # de cheval. 
4. Fractionner le projet fonctions réutilisables et un code rigourement structuré.

🕹️GameZone Inc. a fournit une vidéo du résulat désiré et vous engage pour les deux prochaines semaines en vous payant jusqu'à 3000$ selon le résultat reçu.  Votre résultat à l'écran doit correspondre parfaitement à ce vidéo afin d'obtenir le cachet entier...

## Présentation de 🕹️GameZone Inc.

https://github.com/user-attachments/assets/cb7e5b93-279e-4494-a04f-9a7786aa3121


> ATTENTION: Ne pas tenir compte du vacillement de l'écran lors de l'avancemenet d'un cheval. Il existe deux méthodes d'affichage à l'écran et comme je vous demande la plus simple, ce sintillement est normal et acceptable (limitation de la console).

## Spécificatons techniques (-1pt par manque)
1. Respecter l'ensemble des demandes du client, incluant les demandes faites dans le code, les TODO !
2. Votre nom doit apparaître sur la première ligne du code.
3. Avant la remise, il faut placer la variable `WAIT_FOR_SPACE_KEY` à `false` afin d'annuler les demandes d'appuie sur la barre d'espacement.
4. Aucun `cout` ne seras permis dans la fonction `theShawiDerby()`.
5. Retourner le tout au client avant la date de remise en format `.zip` en prennant bien soin de compresser l'ensemble du projet incluant le fichier de solution sinon 🕹️GameZone Inc. refusera simplement le projet et appliquera 10% de pénalité par dépôt.

## Spécifications générales
1. Avoir du plaisir à programmer ce projet car il représente essentiellement le type de raisonnement que vous aurez besoin d'avoir tout au long de votre carrière de programmeur(euse). 

<p align="Center"><img src="./images/end.png" alt="drawing" width="150"/></p>

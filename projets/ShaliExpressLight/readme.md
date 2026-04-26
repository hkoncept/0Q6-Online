<p align="center"><img src="../../includes/logo.svg" alt="drawing" width="100"/></p>
<h4 align="center">0SH - Structure de données</h4>
<h1 align="center">Projet #3 (10%) - ShaliExpress Light</h1>
<p align="center"><img src="./images/shali-express.svg" alt="drawing" width="550"/></p>

**Shali Express**, une entreprise œuvrant dans la vente de produits informatiques en ligne, vous a mandaté afin de développer une preuve de concept de chargement de sa [base de données](./_bin/data.zip).

Ils désirent pouvoir charger leurs produits en mémoire dans une structure de données centrale et effectuer un test de modification.

Le test nommé `runProductUpdateTest()` devra démontrer que la modification locale (dans le test) d’un `product` sélectionné aléatoirement se répercute dans la structure de données centrale.

Ils ont déjà programmé une [solution Visual Studio](./_bin/ShaliExpress.zip) de base à utiliser et vous demandent de ne rien changer au code présent à l'exception des éléments commentés.

Leur équipe d’experts à l’interne a statué que seul le plus petit fichier de données sera utilisé afin d’effectuer le test et vous demande alors de fixer la taille de votre structure de données à `1500` éléments possibles.

> ATTENTION : **Shali Express** exige du code 100 % en anglais.

## StaticHashMap
**Shali Express**, soucieuse de la rapidité d’accès aux données, vous demande de créer une structure de données de type `[clé, valeur]` nommée `StaticHashMap`, où les produits seront enregistrés dans un `Node` sur le `Heap`. L’adresse mémoire de chacun des `Node` sera sauvegardée dans un tableau régulier `table[1500]`, initialisé à `nullptr`.

Étant donné qu’un `Node` n’a pas besoin de méthodes, une `struct` suffit dans ce cas. `Node` contiendra un attribut `key` afin de sauvegarder la clé (code de produit) ainsi qu’une `value` responsable de sauvegarder la donnée elle-même (ici un produit).

**Shali Express** souhaiterait pouvoir, dans le futur, utiliser `StaticHashMap` afin de sauvegarder tout type de données. Vous devez donc utiliser les `template`.

__StaticHashMap__ devra posséder ces méthodes :

1. `hash()` : Fonction de hachage obtenant une clé en paramètre (ici le **code** de produit) et retournant sa valeur entière.
2. `put()` : Ajout d’un produit dans la structure de données en fournissant en paramètre la clé (**code** de produit) ainsi que la valeur (le **produit**).
3. `get()` : Obtention d’un pointeur sur le **produit** dont le code est passé en paramètre.
4. `getRandomElement()` : Retourne un élément (produit) aléatoirement.
5. `~StaticHashMap()` : Destructeur permettant de libérer la mémoire.
6. `StaticHashMap()` : Un constructeur au besoin.

## runProductUpdateTest()
C’est à cet endroit que les tests de `StaticHashMap` s’effectueront :

1. Chargez les produits depuis le fichier et stockez-les dans une `map` (`StaticHashMap`).
2. Enregistrez dans `productPtr` un produit au hasard dans la map et affichez le produit associé à l’écran.
3. Modifiez la marque du produit de `productPtr` et affichez à nouveau.
4. Allez chercher le même produit depuis la **structure de données** et affichez-le.

> Le test sera considéré fonctionnel si les deux derniers affichages sont identiques et que la mémoire demeure stable.

## Exemple d’affichage
```plaintext
ShaliExpress (ESC pour quitter)
------------------------------------------------------------------------------------------
Sélection aléatoire du produit #000162 dans la base de données
------------------------------------------------------------------------------------------
Original :               | #000162 | Sony            | Pro-Console-3106       |   69.93$ |
Modification locale :    | #000162 | ShaliExpressPro | Pro-Console-3106       |   69.93$ |
Original :               | #000162 | ShaliExpressPro | Pro-Console-3106       |   69.93$ |
------------------------------------------------------------------------------------------

Appuyez sur une touche pour lancer le test à nouveau...
```

- Appuie sur la barre d’espacement.

```plaintext
ShaliExpress (ESC pour quitter)
------------------------------------------------------------------------------------------
Sélection aléatoire du produit #000298 dans la base de données
------------------------------------------------------------------------------------------
Original :               | #000298 | Xiaomi          | Apex-Headphones-4874   |  120.25$ |
Modification locale :    | #000298 | ShaliExpressPro | Apex-Headphones-4874   |  120.25$ |
Original :               | #000298 | ShaliExpressPro | Apex-Headphones-4874   |  120.25$ |
------------------------------------------------------------------------------------------

Appuyez sur une touche pour lancer le test à nouveau...
```

- Appuie sur ESC.

```plaintext
Programme terminé, appuyez sur une touche pour fermer...
```

<hr/>
<p align="center"><img src="../../includes/end.png" alt="drawing" width="150"/></p>

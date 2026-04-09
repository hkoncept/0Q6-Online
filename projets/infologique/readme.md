<p align="center"><img src="../../includes/logo.svg" alt="drawing" width="100"/></p>
<h4 align="center">0SH - Structure de données</h4>
<h1 align="Center">Projet #2 (10%)</h1>
<h1 align="Center">🧾 Infologique Inc. 🧾</h1>


**Infologique Inc.**, une entreprise œuvrant dans la vente de logiciels, souhaite créer une application de vente au détail (POS) afin de la proposer à sa clientèle travaillant dans la vente au détail (dont **Atlas Informatique**). Il vous demande de créer une preuve de concept de structure de données permettant la création de reçus d'achat pour une caisse enregistreuse munie d'un lecteur de code-barres. Comme **Infologique Inc.** est située en France, elle est consciente qu'elle ne pourra pas vous fournir le matériel nécessaire aux tests avec le lecteur de code-barres. Elle désire que vous soyez en mesure de lui envoyer une solution Visual Studio capable de simuler la création de reçus de vente et de reproduire de réels achats. **Infologique Inc.** possède la [base de données](./_bin/products.dat) des produits offerts par son client.

> ATTENTION: **Infologique Inc.** exige du code 100% en anglais.
## Consignes
Placez votre algorithme dans la solution Visual Studio présente dans Léa.
## Affichage des produits

1. Créer la classe `Product` incluant les sections que vous avez vues en classe ainsi qu'une surcharge de l'opérateur de sortie.
2. Créer une structure de données de liste chaînée (classe `ProductList`) permettant de regrouper les données des produits disponibles qui contiendra au minimum :
   1. Un attribut `head` qui pointe sur le premier élément qui sera une `struct` nommée `Node` qui, à son tour, contiendra :
      1. Un attribut `data` de type `Product`.
      2. Un attribut `next` de type `Node` initialisé à `nullptr` par défaut.
      3. Un constructeur permettant de créer un nouveau `Node`.
         > On utilise `struct` pour `Node` car les attributs seront par défaut public et cela est convenable car il n'est accessible que par `ProductList`.
   2. Une fonction `add(Product)` qui servira à créer un nouveau `Node` sur la Heap.
   3. Une fonction `print()` qui affichera la liste des produits à l'écran.
   4. Une fonction `getCount()` qui retournera le nombre total de produits à l'écran.
   5. Un destructeur pour libérer l'espace mémoire des `Node` aloué sur la Heap.
3. Créer une fonction `loadProductsFromFile(ProductList)` de lecture des produits depuis le fichier `products.dat` :
   1. Lire l'ensemble des données d'un produit dans des variables distinctes.
   2. Créer un nouveau produit en utilisant son constructeur.
   3. Ajouter le nouveau produit dans une nouvelle `Node` de `ProductList` en assignant le produits à `data`.
4. Effectuer l'affichage des produits à l'écran selon le modèle attendu.
### Résultat attendu
```plaintext
-----------------------------------------------------------------
| #SKU    | BRAND           | MODEL                  |   PRICE  |
-----------------------------------------------------------------
| #284162 | Western Digital | WD Black SN850 1To     | 2065.12$ |
| #602855 | Netgear         | Nighthawk AX12         | 1534.69$ |
| #298905 | Brother         | HL-L2350DW             | 1291.80$ |
| #182945 | Logitech        | MX Keys                |  956.09$ |
| #573207 | Dell            | XPS 13                 | 1795.48$ |
[...]
| #016246 | Kingston        | Fury Beast 16Go DDR5   |  380.32$ |
| #039601 | Netgear         | Nighthawk AX12         |  418.67$ |
| #267444 | Brother         | HL-L2350DW             |  245.18$ |
| #392085 | Razer           | DeathAdder V2          | 1606.88$ |
-----------------------------------------------------------------

Appuyez sur une touche pour lancer le test de nettoyage de mémoire...
```

```plaintext
Lancement du test de nettoyage de mémoire.
Vérifiez la taille de mémoire utilisée par TP2-Infologique dans le Gestionnaire des tâches.
La mémoire utilisée devrait demeurer relativement stable, si elle augmente significativement, le test échoue!

Appuyez sur une touche pour arrêter le test.
..........................................................................................................................................................................................................................................................................................................................................................
```

### Provoquez une problématique de création de Zombies
1. Commentez la ligne qui libère l'espace mémoire de la heap d'un des élément de la liste.
2. Relancez votre solution et observez à quelle vitesse l'espace mémoire augmente.  On se croyait dans un logiciel de la suite Adobe 😂😂😂 ! 
3. Replacez le code original et revérifiez que la mémoire demeure stable.

> 😂 Vous êtes maintenant un pro de la gestion de la mémoire !

<hr/>
<p align="Center"><img src="./images/end.png" alt="drawing" width="150"/></p>

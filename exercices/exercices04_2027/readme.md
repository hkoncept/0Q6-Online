<p align="center"><img src="../../includes/logo.svg" alt="drawing" width="100"/></p>
<h4 align="center">0SH - Structure de données</h4>

# 🏋🏻‍♂️ Exercices 04 - Les conteneurs 🏋🏻‍♂️

Lien vers la [documentation](https://cplusplus.com/reference/stl/).

## Consignes

Effectuez l'ensemble des ces exercices en utilisant un minimum de code, utilisant les avantages des conteneurs associatifs `map` et `set`.

## Base de données à utiliser

Dans ce projet, afin d'éviter de devoir lire depuis des fichiers et ainsi se concentrer sur l'apprentissage des conteneurs, nous simulerons une [base de données `hardcodée`](./includes/data.md).

# 🏗 Question 01 - Classes ou struct

Créez les structures de classes appropriées. Si le projet compile, ce numéro est complété.

# ⌛ Question 02 - Loaded

Chargez les produits dans une structure de données associative de type `map`. Affichez ensuite l'ensemble des produits à l'écran depuis une fonction [printProducts()](./includes/printProducts.md).

# 📦 Question 03 - LinkMe

Pour ce numéro vous serez amené à inclure un objet mémoire dans un autre objet mémoire. Un objet mémoire `Category` devra être présent dans chacun des `Product`.

Chargez en mémoire l'ensemble des `Category` dans un conteneur et faites ensuite la même chose pour les `Product`. En troisième lieu, associez la bonne `Category` à chacun des `Product`.

À ce stade, vous devriez être en mesure d'accéder à la catégorie d'un produit de cette façon :

```cpp
product.getCategory()
```

Créez ainsi une fonction [printProductsWithCategory()](./includes/printProductsWithCategory.md) qui s'occupera d'afficher les produits ainsi que le nom de la catégorie associée.

# Question 04 - GroupBy

Reprenez la première partie du code de la `question03`, la liaison des catégories, afin d'être en mesure d'afficher tous les produits regroupés par catégorie.

Créer donc une fonction `printProductsByCategory` que vous lancerez une première fois avec [ce résultat](./includes/printProductsByCategory.md).

Le client vous demande maintenant de traduire les catégories en français :

```cpp
categories["CPN"].setName("Composants");
categories["PER"].setName("Périphériques");
categories["STO"].setName("Enregistrement");
categories["NET"].setName("Réseautique");
categories["LAP"].setName("Portables");
```

Relancez `printProductsByCategory` et vous devriez obtenir [ce résultat](./includes/printProductsByCategoryFR.md), avec les noms de catégories en français.

# Question 05 - GetBrands

Créez une fonction `getBrands` qui sera utilisée afin de remplir une liste déroulante des marques de produits informatique sur le site web, uniques et triée en ordre alphabétique.

Simulez l'affichage de la liste à l'écran avec [printBrands](./includes/printBrands.md).

<hr><p align="Center"><img src="../../includes/end.png" alt="drawing" width="150"/></p>

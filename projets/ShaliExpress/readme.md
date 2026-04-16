<p align="center"><img src="../../includes/logo.svg" alt="drawing" width="100"/></p>
<h4 align="center">0SH - Structure de données</h4>
<h1 align="Center">Projet #3 (10%)</h1>
<p align="Center"><img src="./images/shali-express.svg" alt="drawing" width="550"/></p>

**Shali Express**, une entreprise œuvrant dans la vente de produits informatiques en ligne, vous a mandaté afin de développer une preuve de concept du `cart` (panier d'achat) de leur nouveau site web.

Ils désirent pouvoir charger leurs produits en mémoire depuis des [fichiers de données de tailles variables](./_bin/data.zip) afin de créer des centaines de `cart` possédant des produits **aléatoires**.

Ils demandent à ce que vous **prouviez** qu'un `product` dans un `cart` se mettra automatiquement à jour dans le cas d'un changement dans la base de données centrale (accessible sous le nom de `products`), de même que le total du panier lors d'un changement de **quantité unitaire** désiré par le client.

Leur équipe d'experts à l'interne ne s'entend pas sur le type de structure de données à utiliser, mais insiste pour avoir le contrôle total du code des structures `product` et `cart`.

Ils ont préparé la solution à utiliser afin de programmer la preuve de concept dans le projet `ShaliExpress`. Cette solution inclut du code partagé que l'entreprise possédait déjà, ainsi qu'un projet `IssueDemonstration` qui présente la problématique actuelle à résoudre.

> ATTENTION : **Shali Express** exige du code 100 % en anglais.

## Logique à respecter

Au lancement de la preuve de concept, **Shali Express** souhaite une vérification de l'existence de tous les fichiers présents dans la structure de configuration actuelle. Ce code doit être assez robuste pour supporter un changement des **données de configuration**.

Elle souhaite ensuite que la preuve de concept démarre les tests de performance avant de charger la base de données officielle qui proviendra du fichier pointé par `onlineConfigIndex`.

Après les tests de performance, **Shali Express** souhaite que la preuve de concept génère un nombre de `cart` défini par `cartSimulationCount` en mémoire, contenant chacun entre 1 et 10 produits sélectionnés aléatoirement dans la structure de données choisie.

**Shali Express** demande à ce que vous fassiez la preuve que les changements effectués directement sur un produit se répercutent dans le `cart`, ce qui inclut le prix de vente. C'est leur décision d'affaires !

Le test d'assurance qualité final prouvera l'utilisation judicieuse de la mémoire dans une boucle infinie de :

1. Chargement des produits pointés par `onlineConfigIndex`.
2. Génération en mémoire de `cartSimulationCount` paniers.
3. Libération de l'ensemble de la mémoire utilisée.

> 😂 Vous êtes maintenant un pro de la gestion de la mémoire !

<hr/>
<p align="Center"><img src="./images/end.png" alt="drawing" width="150"/></p>
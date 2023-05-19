# Correction du MCD 📝

D'abord, bravo pour ton travail sur ton MCD 🎉! Tu as bien utilisé la méthode MERISE, c'est super ! 

Cependant, après analyse, voici quelques retours et suggestions pour améliorer encore ton modèle :

## Relations entre les entités 🧩

✅ Ta compréhension des relations entre les entités USER, ORDER et PRODUCT est très claire, bravo pour ça ! Tu as bien géré la cardinalité entre USER et ORDER (0,n) et (1,1), ainsi que celle entre ORDER et PRODUCT (1,n) et (0,n).

🚀 Cependant, voici une suggestion d'amélioration :

## Ajout d'une relation entre ORDER et ADDRESS 🏠 ↔️ 📦

- **Il serait intéressant d'ajouter une relation HAS entre ORDER et ADDRESS :** En effet, une commande peut être livrée à une adresse différente de celle de l'utilisateur. Donc, la cardinalité serait (1,1) du côté de ORDER et (0,n) du côté d'ADDRESS.

## Relation 'Like' entre USER et PRODUCT 💖

✅ Tu as bien défini une relation "Like" entre USER et PRODUCT, mais la cardinalité pourrait être affinée.

 Voici comment je vois les choses :

- **Un utilisateur peut liker plusieurs produits :** donc, la cardinalité maximale de la relation "Like" du côté utilisateur serait "n".
- **Un produit peut être aimé par plusieurs utilisateurs :** donc, la cardinalité maximale de la relation "Like" du côté du produit serait également "n".
- **Un utilisateur ne peut liker qu'une seule fois un produit spécifique :** donc, la cardinalité minimale de la relation "Like" du côté de l'utilisateur serait "0".
- **Un produit ne peut recevoir qu'un seul like d'un utilisateur spécifique :** donc, la cardinalité minimale de la relation "Like" du côté du produit serait aussi "0".

## 🚀 Pour aller plus loin

Je souhaitait te présenter un outil vraiment génial pour réaliser des schémas pour les bases de données : [Lucidchart](https://www.lucidchart.com/). 🛠️ 

C'est incroyablement intuitif ! C'est toujours un plus d'avoir une variété d'outils dans ton arsenal de développeur. N'hésite pas à l'explorer, il rend la conception de bases de données beaucoup plus facile.

J'espère que ces commentaires te seront utiles pour perfectionner ton MCD 🚀. N'oublie pas, la pratique et les retours sont la clé pour progresser. Continue sur cette voie 🎯 !

N'hésite pas à me faire part de tes questions ou si quelque chose n'est pas clair, je serai ravi de t'aider.


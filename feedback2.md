# Parcours S06  🔥
## Feedback 2

🎉 Bravo pour ton implication dans ce parcours! Il y a de nombreux aspects que tu as bien gérés. Cependant, comme dans tout code, il y a toujours de la place pour amélioration. Voici mes suggestions:

### 2. Lister tous les profs:

👍 Point respecté, Bravo!

💡 Voici quelques axes d'amélioration:

-   **Indentation:** N'oublie pas d'indenter ton code pour plus de lisibilité. Cela facilite aussi le débogage.

### 3. Lister tous les étudiants:

👍 Point respecté, bravo!

### 4. Ajout d'un prof:

Point non respecté

Dans ton intégration HTML, tu as bien créé la route GET, mais tu n’as pas implémenté le bouton pour accéder à la vue pour créer un professeur. Assure-toi d'utiliser correctement le `$router->generate('teachers-add')` pour générer le lien vers le formulaire d'ajout de professeur.

💡 Quelques suggestions pour améliorer ton code HTML:

-   **Vue:** Ton code de vues est bien structuré, mais pour améliorer la maintenabilité, pense à créer des vues partielles pour la barre de navigation et à les inclure dans le header.
    
-   **Mise en page:** Le corps de tes vues manque de marges à droite et à gauche. Il serait judicieux de placer l’ensemble dans un conteneur avec de la marge. Tu peux utiliser les classes de Bootstrap pour cela, comme `container` et les classes de marge (ressource: [Bootstrap Spacing](https://getbootstrap.com/docs/4.0/utilities/spacing/)). N'oublie pas de fermer le conteneur dans la vue du footer.
    

💡 Et enfin, attention à ton Model. Il reste du code de la précédente application oShop qui pourrait te perturber ou te poser problème. Essaye de nettoyer le code qui n'est pas utilisé.

----------

Je suis à ta disposition pour approfondir les points qui te posent problème. Continue comme ça, tu fais du bon travail! J'espère que ces commentaires te seront utiles pour améliorer ton code. N'hésite pas à demander si tu as des questions. 💪😊
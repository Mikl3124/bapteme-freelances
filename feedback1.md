# Parcours S06  🔥
## Feedback 1

🎉 Félicitations pour ton excellent travail sur ce parcours! Voici quelques points clés à noter et à améliorer:

### Clarté du code:

-   **Pour aller plus loin:** Pense à dissocier les routes et à les mettre dans un fichier routes.php pour plus de clarté.
    

### 2. Lister tous les profs:

👍 Point respecté, Bravo!

💡 Cependant, voici quelques axes d'amélioration:

-   **Nom de la méthode:** Le nom de ta fonction, teacher(), pourrait être plus explicite, par exemple list() ou index().
    
-   **Utilisation de Teacher:** Essaie d'utiliser Teacher::findAll() pour plus d'efficacité.
    
-   **Commentaires:** N'oublie pas de commenter ton code pour faciliter sa compréhension.
    

### 3. Lister tous les étudiants:

👍 Point respecté, bravo! Les axes d'amélioration sont les mêmes que pour le point 2.

### 4. Ajout d'un prof:

👍 Point respecté!

💡 Ici aussi, quelques conseils pour améliorer ton code:

-   **Nom des méthodes:** Il est inutile de répéter 'teacher' dans le TeacherController.
    
-   **Commentaires:** Bien fait sur teacherAddPost(), n'oublie pas teacherAddGet().
    

### 5. Ajout d'un étudiant:

👍 Point respecté, très bien pour les commentaires!

### 6. Restreindre l'accès aux utilisateurs:

👍 Point respecté!

💡 Cependant, tu pourrais améliorer encore en considérant ces points:

-   **Validation des entrées:** Pour aller plus loin,vérifie si l'email est non seulement présent, mais aussi valide, et vérifie si le mot de passe a un certain nombre de caractères.
    
-   **Structure du code:** Essaye de séparer la vérification des identifiants de l'utilisateur de la gestion de la soumission du formulaire.
    
-   **Gestion des sessions:** Considère la possibilité de stocker l'objet utilisateur complet dans la session.
    
-   **Gestion des erreurs:** Continue ta gestion des erreurs, c'est très bien fait!
    

### 7. Mettre en place les permissions:

👍 Point respecté!

💡 Quelques points à améliorer:

-   **Organisation du code:** Pour aller plus loin, essaye de mettre les contrôles d'accès de tes routes dans un fichier séparé.
    
-   **Duplication de code:** Fais attention aux copiés / collés. Par exemple, tu as dupliqué la clé 'student_update_get' dans ton tableau $acl.
    

### Bonus - Validation des données:

👍 Bravo pour avoir atteint les bonus!

💡 Pourtant, quelques points à améliorer:

-   **Répétition de code:** Essaye de suivre le principe DRY (Don't Repeat Yourself).
    
-   **Vérification du statut:** Assure-toi de vérifier si le statut est égal à 1 ou 2.
    
-   **Gestion des erreurs de base de données:** Pense à afficher un message d'erreur convivial à l'utilisateur et à enregistrer les détails de l'erreur dans un fichier de logs.
    
-   **Redirection:** Après une opération réussie, affiche un message de succès à l'utilisateur.
    

### Mise à jour d'un prof et d'un étudiant:

👏 Très bon travail! Voici quelques points à noter:

💡 Suggestions d'amélioration:

-   **Gestion des erreurs:** Continue ta gestion des erreurs, c'est très bien fait! N'oublie pas cependant de vérifier également les autres types d'erreurs qui peuvent survenir, comme des problèmes de connexion à la base de données. Attention aux copiés / collés, tu utilises le message d’erreur du statut pour le Teacher.
    
-   **Redirection:** Ta redirection après la mise à jour du professeur ou de l'étudiant est bien faite.
    
-   **Nommage des variables et des méthodes:** La variable $retour pourrait être renommée en quelque chose de plus descriptif comme $updateSuccess.
    
-   **Commentaires:** Tes commentaires sont utiles et aident à comprendre le but de chaque bloc de code. Continue comme ça!
    

### Suppression d'un prof et d’un étudiant:

💡 Suggestions d'amélioration:

-   **Utilisation des méthodes de suppression:** Il est plus sûr de d'abord trouver l'entité à supprimer, puis de vérifier si cette entité existe avant de la supprimer.
    
-   **Gestion des erreurs:** Tu as bien pensé à gérer les erreurs, c'est super! Néanmoins, tu ne renvoies pas le message d'erreur à ta vue. Tu pourrais ajouter 'errorList' => $errorList à ton tableau de données envoyé à la vue pour pouvoir afficher les erreurs.
    

### 🎉 MegaBonus:

**BRAVO** pour être arrivé au megaBonus et avoir implémenté la liste des utilisateurs !!

----------

Je tiens à te féliciter pour ton engagement dans ce parcours. Tu as montré une bonne compréhension des concepts que nous avons abordés jusqu'à présent, et je suis impressionné par la qualité du code que tu as produit.

Continue comme ça, tu fais du bon travail ! J'espère que ces commentaires t'aideront à améliorer ton code. Si tu as des questions, n'hésite pas à demander. 💪😊
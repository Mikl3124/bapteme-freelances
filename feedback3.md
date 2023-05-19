# Parcours S06  🔥
## Feedback 3

Tu as fourni un bel effort dans ce travail. Voyons ensemble comment tu pourrais l'améliorer encore.

## Route racine

Fais attention à ta route racine ‘/’. Actuellement, tu utilises ‘/home’ comme URL, ce qui génère une erreur dès le lancement de l’application. Peut-être voulais-tu utiliser '/' pour l'accueil ?

## Lister tous les profs

👍 Tu as bien respecté ce point, bravo !

💡 Toutefois, je te propose quelques axes d'amélioration :

Il manque le menu dans la vue, ce qui ne facilite pas la navigation. Tu pourrais améliorer cela en découpant ton code HTML avec des templates (.tpl par exemple). C'est-à-dire :

-   Créer des layouts pour ton header et ton footer que tu placerais dans un dossier dédié
-   Créer une vue partielle pour ta barre de navigation
-   Inclure cette vue partielle de navigation dans le header (ainsi tu es sûr de ne pas l'oublier)

Si tu as des questions sur le système de templates, n'hésite pas à me le faire savoir, je serai ravi de t'aider.

De plus, attention à la structure de ton HTML. Dans ton code actuel, tu fermes ton `</body>` avant ton bouton d’ajout et la balise fermante de ta table, ce qui peut poser des problèmes de mise en page.

## Lister tous les étudiants

👍 Tu as bien respecté ce point également, bien joué !

💡 Cependant, il semble que tu aies repris le template des profs, et les étudiants n’ont pas de titre. Fais attention lorsque tu fais du copier-coller.

## Ajout d'un prof

Il semble y avoir un problème ici : la route de ton bouton mène vers la création d’un étudiant et non d'un prof.

## Ajout d'un étudiant

Le bouton fonctionne correctement et la route est bien implémentée, c'est super. Les sélections reprennent bien les professeurs, c'est parfait.

En revanche, tu sembles oublier de renseigner le `teacher_id` dans ta fonction d’insert() du Model Student, c’est pour cette raison que l’enregistrement génère une erreur.

De plus, bravo pour la validation des champs firstname, lastname et status. Tu t'assures ainsi que les données sont conformes à ce que tu attends.

💡 Cependant, essaie d'être cohérent dans tes messages d'erreur. Par exemple, pour le firstname, tu indiques "Le nom est vide !" alors que tu vérifies en fait le prénom.

### Commentaires de code

Ton code est bien commenté, ce qui te permettra de t’y retrouver plus facilement, ou de faciliter la reprise du code par une autre personne. C'est une bonne habitude à conserver.

----------

En somme, tu as déjà bien avancé. Avec un peu plus d'attention aux détails, ton code pourrait être encore meilleur. Continues comme ça, chaque erreur est une occasion d'apprendre et de progresser. Tu fais du bon travail !
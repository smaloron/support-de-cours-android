# Partie 4 : Gestion des Données

Félicitations pour avoir construit une "maison" applicative bien organisée, avec plusieurs pièces et des couloirs pour
se déplacer. Mais que se passe-t-il si vous voulez garder des photos de famille sur la cheminée, ou une liste de courses
sur le frigo ? Pour l'instant, dès que vous quittez la maison, tout disparaît.

Cette partie, "Gestion des Données", est consacrée à donner une mémoire à votre application. Nous allons explorer deux
types de mémoire :

1. **La mémoire interne (Persistance locale)** : Comment stocker des informations directement sur l'appareil de l'
   utilisateur ? Nous commencerons par des notes simples sur un post-it (`SharedPreferences`), puis nous construirons
   une véritable bibliothèque de données bien organisée avec `Room`.
2. **La mémoire externe (Réseau)** : Comment communiquer avec le monde extérieur ? Nous apprendrons à interroger des
   serveurs distants (API REST) pour récupérer des informations fraîches et à jour, comme les dernières actualités ou la
   météo.

Pour manipuler ces données, qui peuvent prendre du temps à être récupérées (surtout via le réseau), nous devrons aussi
apprendre à travailler en **asynchrone** avec les **Coroutines Kotlin**, afin de ne jamais bloquer l'interface
utilisateur.

À la fin de cette partie, votre application ne sera plus un simple outil interactif, mais un véritable compagnon capable
de se souvenir, d'apprendre et de se connecter au monde.

---


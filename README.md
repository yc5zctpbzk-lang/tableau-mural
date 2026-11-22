# Tableau mural

Tableau de bord plein écran pour un iPad fixé au mur (HomeKit) : heure, météo, boutons de scènes et mode nuit automatique.

## Personnaliser
Tout se règle en haut du script dans `index.html` :
- `VILLE` : nom et coordonnées (latitude, longitude) pour la météo (Open-Meteo, sans clé).
- `NUIT_DEBUT` / `NUIT_FIN` : heures du mode nuit.
- `SCENES` : les boutons. Chaque bouton lance le Raccourci iOS qui porte exactement le nom indiqué dans `raccourci`.

## Installation sur l'iPad
1. Ouvrir l'adresse GitHub Pages du dépôt dans Safari.
2. Partager > Sur l'écran d'accueil.
3. Créer dans l'app Raccourcis un raccourci par bouton, avec le même nom, et l'action « Contrôler la maison ».

Ajouter `#nuit` à l'adresse force l'affichage du mode nuit.

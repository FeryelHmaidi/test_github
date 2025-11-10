# Nom de projet:  Système de Gestion des Étudiants

# présenté par**Hmaidi Feryel**


#  Description du projet: 

Cette application est un mini-projet web CRUD permettant de gérer une liste d’étudiants.  
Elle a été réalisée avec **HTML, CSS et JavaScript pur** et fonctionne entièrement dans le navigateur, sans frameworks externes comme vous nous avez indiqué.
L’application permet d’ajouter, modifier, supprimer et visualiser des étudiants, avec des fonctionnalités de tri, recherche et filtrage.

#  Technologies utilisées
- **HTML5** → structure de la page  
- **CSS3** → design, responsive et animations  
- **JavaScript (ES6)** → logique et interactivité  
- **LocalStorage** → persistance des données  

#  Fonctionnalités Clés Implémentées
- **Opérations CRUD** : Ajouter de nouveaux étudiants, consulter la liste, modifier les détails existants et supprimer des entrées.  
- **Persistance Locale** : Les données sont stockées dans le localStorage du navigateur et persistent entre les sessions.  
- **Tri** : Trier les étudiants par nom, âge ou note (croissant/décroissant).  
- **Recherche** : Rechercher par nom d'étudiant (insensible à la casse).  
- **Filtrage** : Filtrer par note (par exemple, afficher uniquement les étudiants avec une note spécifique).  
- **Animations CSS** : Effets de fondu en entrée pour les nouveaux éléments, glissement en sortie pour les suppressions, et effets de survol.
- **Manipulation du DOM** : Création, mise à jour et suppression dynamiques des éléments.  
- **Interface Utilisateur** : Formulaire et tableau simples et responsives.



## Comment Utiliser🤔🧠?
💡
1. Ouvrez le fichier `index.html` dans **VS Code** ou tout éditeur de texte.  
2. Exécutez-le sur un navigateur web moderne (**Chrome**, **Firefox**, etc.).  
3. Ajoutez des étudiants via le formulaire.  
4. Utilisez les options de recherche, tri et filtrage pour consulter vos données.  
5. Les données sont automatiquement sauvegardées localement — rafraîchissez la page pour voir qu'elles persistent.

## Explication du fonctionnement
- **Structure des Données** :  
  Les étudiants sont stockés sous forme d’objets avec `id`, `nom`, `age` et `note`.  
  L’`id` est un horodatage pour garantir l’unicité.

- **Persistance** :  
  Le `localStorage` sauvegarde le tableau des étudiants en JSON. Il se charge automatiquement au rafraîchissement de la page.

- **CRUD** :  
  Le formulaire gère l’ajout et la mise à jour ;  
  les boutons dans le tableau permettent la modification et la suppression.

- **Tri** :  
  Cliquez sur les en-têtes du tableau pour trier par colonne (bascule croissant/décroissant).

- **Recherche/Filtrage** :  
  Le filtrage et la recherche sont en temps réel, selon les entrées utilisateur.

- **Animations** :  
  Clés CSS pour le fondu en entrée (nouveaux éléments) et le glissement en sortie (suppressions).

- **DOM** :  
  Tous les éléments sont créés et manipulés dynamiquement via JavaScript.

Cette application est **légère** et fonctionne entièrement dans le navigateur, sans serveur.


##  Lien du rendu final (GitHub Pages)
👉 Voir le projet en ligne: (https://hmaidi-feryel.github.io/hmaidi_feryel_gestion_etudiants/)


##  Dépôt GitHub
👉 (https://github.com/hmaidi-feryel/hmaidi_feryel_gestion_etudiants)



## 🧩 Nouveautés explorées
- LocalStorage pour persistance des données  
- Création dynamique et manipulation du DOM  
- Animations CSS pour UX  
- Design responsive adapté mobile, tablette et desktop  

## 🧠 Difficultés rencontrées:
- Gestion des identifiants uniques pour les étudiants  
- Mise à jour dynamique du tableau après modification  
- Tri et filtrage combinés avec la persistance des données  


## 💡 Solutions apportées
- Utilisation de `Date.now()` pour générer des `id` uniques  
- Fonction `renderStudents()` centralisée pour rafraîchir le tableau après chaque action  
- Tests et validation progressive de chaque fonctionnalité  
- j'ai fait des recherches sur google et youtube pour apprendre des nouveaux choses utiles et qui me permettent de finir le projet avec succés 
- De plus j'ai regardé des videos pour mieux comprendre le DOM et l'appliquer sur mon projet

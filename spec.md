# Spécifications du projet – Chef à la Maison 🍴

---

# 1. Présentation du projet

**Chef à la Maison** est une application web interactive dédiée aux recettes de cuisine.
Elle permet aux utilisateurs de découvrir, consulter et organiser différentes recettes dans une interface simple et moderne.

L'application est développée avec **HTML, CSS et JavaScript**, et fonctionne directement dans le navigateur sans serveur backend.

L'objectif du projet est de créer une application web interactive permettant de pratiquer :

- la manipulation du **DOM avec JavaScript**
- la gestion des **événements utilisateurs**
- l'organisation d'une **interface web moderne**
- la création d'une application web simple et fonctionnelle.

---

# 2. Objectif du projet

Le projet a pour objectif de développer une application permettant aux utilisateurs de :

- consulter des recettes de cuisine
- rechercher des recettes facilement
- ajouter leurs propres recettes
- sauvegarder leurs recettes préférées
- accéder aux détails complets d'une recette

Cette application vise à offrir une expérience simple et intuitive pour les amateurs de cuisine.

---

# 3. Public cible

Cette application est destinée à :

- les amateurs de cuisine
- les étudiants
- toute personne souhaitant découvrir ou partager des recettes.

---

# 4. Fonctionnalités principales

## 4.1 Navigation

L'application fonctionne comme une **Single Page Application (SPA)** avec plusieurs sections :

- Accueil
- Toutes les recettes
- Favoris
- Détail d'une recette

La navigation se fait sans rechargement de page.

---

## 4.2 Catalogue de recettes

Les recettes sont affichées sous forme de **cartes interactives** contenant :

- une image
- le titre de la recette
- la catégorie
- le niveau de difficulté

Un clic sur une carte permet d'accéder à la **page de détail de la recette**.

---

## 4.3 Recherche de recettes

Une barre de recherche permet de trouver rapidement une recette.

La recherche s'effectue sur :

- le titre de la recette
- la description.

---

## 4.4 Catégories

Les recettes sont classées par catégories :

- Entrées
- Plats
- Desserts
- Boissons

Un filtre permet d'afficher uniquement les recettes d'une catégorie.

---

## 4.5 Favoris

Les utilisateurs peuvent ajouter ou retirer une recette de leur liste de favoris.

Les recettes favorites sont enregistrées dans le **LocalStorage du navigateur**.

---

## 4.6 Ajout de recettes

Un formulaire permet d'ajouter une nouvelle recette.

Les informations demandées sont :

- Titre
- Description
- Catégorie
- Niveau de difficulté
- Temps de préparation
- Nombre de portions
- Image
- Vidéo YouTube (optionnelle)
- Liste des ingrédients
- Étapes de préparation

Les recettes ajoutées apparaissent automatiquement dans la liste des recettes.

---

## 4.7 Mode administrateur

Un mode administrateur permet de gérer le contenu du site.

L'administrateur peut :

- modifier une recette
- supprimer une recette.

---

# 5. Interface utilisateur

L'interface comprend plusieurs éléments :

- une barre de navigation principale
- une galerie de recettes
- des filtres de recherche et de catégories
- des cartes de recettes interactives
- des formulaires d'ajout et de modification
- des modales pour certaines actions.

Le design est **responsive**, ce qui permet au site de s'adapter aux :

- ordinateurs
- tablettes
- smartphones.

---

# 6. Architecture technique

Le projet utilise les technologies suivantes :

**HTML**

- structure de l'application
- organisation des pages et des sections.

**CSS**

- design de l'interface
- mise en page
- responsive design.

**JavaScript**

- gestion des interactions utilisateurs
- affichage dynamique des recettes
- filtrage et recherche
- gestion des favoris.

Les données des recettes sont stockées dans le **LocalStorage du navigateur**.

---

# 7. Limitations

L'application fonctionne uniquement côté client.

Les données :

- sont stockées dans le navigateur
- peuvent être supprimées si le cache du navigateur est vidé.

---

# 8. Améliorations futures

Plusieurs améliorations peuvent être envisagées :

- développement d'une **version mobile**
- partage des recettes sur les réseaux sociaux.

---

# README - Projet Mon Service Public

## Structure du projet
Le projet est divisé en plusieurs sections : un en-tête avec une barre de recherche, une barre de navigation avec des menus déroulants, un fil d'Ariane pour la navigation, un tableau de bord avec plusieurs rubriques, et enfin un pied de page contenant des informations et des liens.

### Header (En-tête)
- **Bootstrap Flexbox** : Le header utilise le système Flexbox de Bootstrap (`d-flex`, `justify-content-between`, `align-items-center`) pour aligner le logo à gauche et la barre de recherche à droite.
- **Barre de recherche** : La barre de recherche est intégrée dans un conteneur de formulaire avec des éléments stylisés en CSS. Le bouton de recherche utilise un **dégradé linéaire** avec `linear-gradient` pour un effet visuel attrayant.

### Barre de navigation
- **Grille CSS** : La barre de navigation est structurée à l'aide de **grid layout** (`grid-template-columns`) pour répartir les éléments de manière égale. Cela permet de maintenir une disposition fluide et adaptée aux différentes tailles d'écran.
- **Menus déroulants** : Chaque élément de la barre de navigation utilise des **menus déroulants** avec la classe `.dropdown-content`. Ces sous-menus apparaissent au survol de l'élément parent grâce à une combinaison de CSS et de JavaScript natif de Bootstrap.

### Contenu principal (Tableau de bord)
- Le contenu principal est organisé en deux colonnes grâce à la grille de Bootstrap. La colonne de gauche contient les rubriques principales, et la colonne de droite affiche des astuces et actualités.
- **Utilisation de Flexbox** : Les rubriques à l'intérieur des colonnes utilisent `display: flex` pour garantir un espacement uniforme et un alignement vertical correct.
- **Responsive design** : Les colonnes se réorganisent automatiquement sur des écrans plus petits grâce aux classes Bootstrap **`col-lg-9`** et **`col-lg-3`**, permettant ainsi une expérience utilisateur optimale sur différents appareils.

### Fil d'Ariane
Le fil d'Ariane (`breadcrumb`) est utilisé pour afficher la navigation hiérarchique du site et permettre à l'utilisateur de revenir aux pages précédentes.

### Pied de page
- **Dispositif responsive** : Le pied de page est construit avec **Flexbox** pour disposer les éléments horizontalement. Sur les écrans plus petits, il se réorganise en colonnes grâce aux règles de **media queries**.
- Le pied de page contient plusieurs sections, notamment des liens vers l'assistance, des informations légales, et des organismes partenaires. Chaque lien est stylisé pour rester lisible et intuitif, même sur des appareils mobiles.

## Utilisation de Bootstrap
Bootstrap est principalement utilisé pour :
- La gestion de la mise en page responsive avec son système de grilles (`container-fluid`, `row`, `col-*`).
- Les composants interactifs comme les **menus déroulants** et la **barre de navigation**, simplifiant la création d'une interface utilisateur réactive.
- Les **classes utilitaires** telles que `d-flex`, `justify-content-between`, et `align-items-center` permettent de gérer les alignements de manière efficace sans code CSS supplémentaire.

## Justifications CSS
- **Grille CSS** : La barre de navigation est conçue avec un `grid-template-columns` pour garantir que les éléments se répartissent uniformément et que la mise en page reste flexible.
- **Dégradé sur les boutons** : Le bouton de recherche est stylisé avec un dégradé de couleurs pour ajouter de la profondeur visuelle sans surcharger l'interface.
- **Effet hover** : Les liens dans les menus déroulants et le pied de page ont un style de **hover** pour améliorer l'interaction utilisateur.

## Responsivité
Le design est entièrement responsive, avec l'utilisation de **media queries** pour adapter la mise en page aux différentes tailles d'écran (notamment pour les écrans de moins de 768px et 576px). Cela assure une navigation fluide sur mobile comme sur ordinateur.

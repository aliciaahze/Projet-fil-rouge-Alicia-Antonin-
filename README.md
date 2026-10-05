# CampusLink - FR01 (HTML/CSS)

Maquette statique de **CampusLink**, une plateforme de gestion du campus (salles, équipements, incidents). Projet fil rouge Ynov B1 (2026-2027), mission FR01.

Dépôt GitHub : https://github.com/aliciaahze/Projet-fil-rouge-Alicia-Antonin-

## Auteurs

- [Prénom Nom]
- [Prénom Nom]

## Lancer le projet

1. Télécharger ou cloner le dépôt.
2. Ouvrir le dossier `CampusLink` dans VSCode.
3. Ouvrir `index.html` dans un navigateur (ou clic droit puis "Open with Live Server").

Aucune installation n'est nécessaire : le projet utilise uniquement du HTML et du CSS, sans JavaScript.

## Pages de la maquette

| Écran | Fichier |
|---|---|
| Tableau de bord | `index.html` |
| Salles | `pages/salles.html` |
| Équipements | `pages/equipements.html` |
| Incidents | `pages/incidents.html` |
| Détail d'un incident | `pages/incident-detail.html` |
| Déclaration d'un incident | `pages/declaration.html` |

## Arborescence

```
CampusLink/
├── index.html
├── pages/
│   ├── salles.html
│   ├── equipements.html
│   ├── incidents.html
│   ├── incident-detail.html
│   └── declaration.html
├── css/
│   └── style.css
├── images/
└── README.md
```

## Choix techniques

- **HTML sémantique** : `header`, `nav`, `main`, `section`, `article` et `footer`, un seul `h1` par page et des titres hiérarchisés.
- **CSS organisé** : une seule feuille `css/style.css` partagée par toutes les pages, découpée en parties commentées, avec des variables de couleurs dans `:root`.
- **Flexbox** pour le menu de navigation et l'en-tête.
- **Grid** pour l'affichage des cartes (`repeat(auto-fit, minmax(220px, 1fr))`).
- **Responsive, mobile first** : le style de base vise le téléphone, puis une règle `@media (min-width: 768px)` adapte l'en-tête et le menu aux grands écrans.
- **Accessibilité** : `lang="fr"`, balise `viewport`, menu avec `aria-label`, page active signalée par `aria-current`, champs de formulaire reliés à leur `label`, groupe de boutons radio avec `fieldset` et `legend`.
- **Standards** : toutes les pages ont été vérifiées avec le validateur HTML du W3C.

## Limites

- Les données (salles, équipements, incidents) sont fictives, elles servent à illustrer la maquette.
- Le formulaire de déclaration n'enregistre rien : il redirige vers la page des incidents.

## Captures d'écran

- Version mobile : [à ajouter]
- Version desktop : [à ajouter]
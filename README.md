# AWS Study

Fiche de révision interactive dédiée à l’architecture cloud AWS et aux certifications **AWS Certified Solutions Architect – Associate (SAA-C03)** et **AWS Certified Solutions Architect – Professional (SAP-C02)**.

## Fonctionnalités

- Synthèse des principaux services et concepts AWS.
- Recherche globale dans le contenu de la fiche.
- Navigation par catégories grâce aux onglets.
- Mode clair et mode sombre.
- Mise en page responsive pour ordinateur, tablette et mobile.
- Impression optimisée (`Ctrl+P` / `Cmd+P`) : les deux parcours de révision sont imprimés intégralement, sans recherche ni navigation.

## Technologies

- HTML5
- CSS3 intégré à la page
- JavaScript natif intégré à la page
- [Font Awesome 6](https://fontawesome.com/) chargé depuis cdnjs pour les icônes
- Feuille de style d'impression (`@media print`) intégrée pour un rendu papier optimal des deux parcours

## Structure du projet

```text
.
├── index.html   # Page principale et contenu de révision
└── README.md    # Documentation du projet
```

## Utilisation

Aucune installation ou compilation n’est nécessaire. Ouvrez simplement `index.html` dans un navigateur moderne.

### Impression

Utilisez la boîte de dialogue d’impression du navigateur (`Ctrl+P` sous Windows/Linux, `Cmd+P` sur macOS). Le rendu `@media print` : affiche automatiquement **les deux parcours** (SAA-C03 et SAP-C02) quelle que soit l’onglet sélectionné, masque la recherche et la navigation, et évite de couper les tableaux, les cartes et les sections de contenu entre deux pages.

> **Remarque hors ligne :** les icônes (Font Awesome) sont chargées depuis un CDN. En l’absence de connexion au moment du chargement, elles peuvent ne pas s’afficher ; le contenu textuel reste entièrement lisible et imprimable.

## Page en ligne

La fiche est disponible en ligne à l’adresse suivante :

<https://alvincangou.github.io/aws-study/>

Pour lancer le projet avec un serveur local, vous pouvez par exemple utiliser l’une des commandes suivantes depuis la racine du dépôt :

```bash
# Python
python -m http.server 8000

# Node.js, si npx est disponible
npx serve .
```

Puis ouvrez [http://localhost:8000](http://localhost:8000) dans votre navigateur pour la commande Python.

## Objectif pédagogique

Ce projet constitue un support de mémorisation et de consultation rapide. Il ne remplace pas la documentation officielle AWS, les examens blancs ni les formations dédiées aux certifications.

## Contribution

Les corrections, mises à jour liées aux évolutions AWS et améliorations de l’interface sont les bienvenues. Pour contribuer :

1. Créez une branche dédiée.
2. Modifiez le contenu ou l’interface dans `index.html`.
3. Vérifiez l’affichage et les fonctionnalités dans un navigateur.
4. Ouvrez une pull request en décrivant les changements effectués.

## Licence

Aucune licence spécifique n’est actuellement indiquée dans ce dépôt.
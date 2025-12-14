Books - Plateforme de Bibliothèque en Ligne

## Description

Ce projet consiste à concevoir un site web simulant une **plateforme de bibliothèque en ligne**. Il permet de se familiariser avec l'utilisation des frameworks CSS les plus courants et de développer un projet simulant un site web réel.

Le site comprend plusieurs pages permettant de naviguer dans un catalogue de livres, consulter des articles de blog et contacter la bibliothèque.

##  Objectifs

- Conception d'un projet type réel
- Familiarisation avec les différents frameworks CSS les plus courants
- Maîtrise des classes utilitaires Bootstrap
- Création d'une interface responsive et moderne

##  Technologies Utilisées

- **HTML5** - Structure sémantique
- **CSS3** - Styles personnalisés
- **Bootstrap 5.3** - Framework CSS principal
- **Bootstrap Icons** - Bibliothèque d'icônes
- **JavaScript** - Interactivité (menu burger, etc.)

## Spécifications Techniques

- **Utilisation maximale des classes utilitaires** provenant des frameworks CSS
- **Au moins 80% des classes** utilisées proviennent de Bootstrap
- **Responsive design** adapté à tous les écrans (mobile, tablette, desktop)
- **Navigation fluide** entre les différentes pages

## Structure du Projet


books/
├── index.html          # Page d'accueil
├── shop.html          # Page boutique
├── post.html          # Page article de blog
├── contact.html       # Page contact
├── style.css          # Styles personnalisés
├── image/             # Dossier des images
│   ├── livre1.png
│   ├── livre2.png
│   └── ...
└── README.md          # Documentation
```

##  Fonctionnalités

### Page d'Accueil (index.html)
- Bannière hero avec promotion
- Section "Featured" avec livres en vedette
- Section "Best Selling Products"
-  Section "Special Products"
- Blog updates
- Newsletter

### Page Boutique (shop.html)
- Barre de recherche
- Filtres par catégories
- Grille de produits responsive
- Articles récents en sidebar

### Page Blog (post.html)
- Article complet avec images
- Galerie d'images
- Formulaire de commentaires
- Navigation entre articles

### Page Contact (contact.html)
- Formulaire de contact
- Informations de localisation
- Coordonnées

## 📱 Responsivité

Le site est entièrement responsive avec des breakpoints Bootstrap :

| Breakpoint | Taille | Comportement |
|------------|--------|--------------|
| Mobile | < 576px | 1 colonne, menu burger |
| Tablette | 576px - 768px | 2 colonnes |
| Desktop | > 768px | 3-4 colonnes, menu horizontal |

## Installation & Utilisation

1. Cloner le repository**

git clone https://github.com/Mika-illou/Boock.git


2. Ouvrir le projet**

# Ouvrir directement index.html dans votre navigateur
open index.html
# Ou utiliser un serveur local (recommandé)

# Puis ouvrir http://localhost:8000


3. **Naviguer dans le site**
- Accueil : `index.html`
- Boutique : `shop.html`
- Blog : `post.html`
- Contact : `contact.html`

## Classes Bootstrap Principales Utilisées

- **Layout** : `container`, `container-fluid`, `row`, `col-*`
- **Composants** : `card`, `btn`, `navbar`, `form-control`
- **Utilitaires** : `d-flex`, `justify-content-*`, `align-items-*`, `gap-*`
- **Espacement** : `m-*`, `p-*`, `mb-*`, `mt-*`
- **Typographie** : `fw-bold`, `text-muted`, `text-danger`
- **Responsive** : `d-none`, `d-md-block`, `col-12`, `col-md-6`

##  Ressources

### Ressources du Projet
- [Google Drive - Assets & Designs](https://drive.google.com/drive/folders/1BkgHVcwK-srz3WG33PK8rKccECcV7tbD?usp=sharing)

### Documentation
- [Bootstrap 5.3 Documentation](https://getbootstrap.com/docs/5.3/)
- [Bootstrap Icons](https://icons.getbootstrap.com/)


## 👤 Auteur

**Mika Illou**
- GitHub : [@Mika-illou](https://github.com/Mika-illou)

## 📝 Licence

Ce projet est réalisé dans un cadre éducatif.

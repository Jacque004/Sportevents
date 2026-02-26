# SportEvents — Plateforme d'événements sportifs

> Projet portfolio : application web de découverte et réservation d'événements sportifs (marathons, tennis, football, cyclisme).

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![Bootstrap 5](https://img.shields.io/badge/Bootstrap-7952B3?style=flat&logo=bootstrap&logoColor=white)

## Aperçu

Site vitrine responsive permettant de :
- **Parcourir** les événements sportifs à la une (carousel, grille)
- **Filtrer** par catégorie (Football, Tennis, Marathon, Cyclisme)
- **Consulter** les détails de chaque événement et **réserver** (formulaire + confirmation)
- **Contacter** l’équipe (formulaire avec sujets : réservation, information, partenariat, recrutement)

## Stack technique

| Couche        | Technologies                          |
|---------------|----------------------------------------|
| Front-end     | HTML5, CSS3, JavaScript (vanilla)      |
| Framework CSS | Bootstrap 5                            |
| Icônes        | Font Awesome 6                         |
| Typographie   | Google Fonts (Plus Jakarta Sans)       |

## Démarrage

1. Cloner le dépôt et ouvrir le dossier.
2. Lancer un serveur local (XAMPP, Live Server, ou ouvrir `index.html`).
3. Accéder à `index.html` dans le navigateur.

```bash
# Exemple avec un serveur Python
python -m http.server 8000
# Puis http://localhost:8000
```

## Structure du projet

```
├── index.html          # Accueil (hero, carousel, partenaires)
├── evenements.html     # Liste des événements + filtres
├── contact.html        # Formulaire de contact
├── css/
│   └── style.css       # Styles personnalisés
├── js/
│   └── main.js         # Filtres, formulaires, animations
├── img/                # Visuels des événements
└── [événements].html   # Pages détail (Roland-Garros, Marathon, etc.)
```

Projet réalisé dans le cadre d’un parcours **Développeur Full Stack**.

---

*Dernière mise à jour : 2025*

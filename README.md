# Aegis Bank - Landing Page "Compte Créateurs"

![Version](https://img.shields.io/badge/version-1.0.0-blue.svg) ![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white) ![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)

<img width="400" height="690" alt="screencapture-127-0-0-1-5500-index-html-2026-05-21-14_13_25" src="https://github.com/user-attachments/assets/0af4e4c0-c168-490c-8947-201c91dd52fe" />

## À propos du projet

Ce projet est la landing page "Compte Créateurs" pour **Aegis Bank**, une néobanque éthique européenne ciblant les créateurs de contenu de 18 à 25 ans (streamers, gamers, artistes digitaux). Lancée pour la mission Q1 2026 (Ref: NAMCOD-2025-Q1-AEGIS), cette interface se positionne comme l'alternative éthique aux acteurs traditionnels (comme Remolut).

Le site met en avant une finance numérique responsable, centrée sur la confidentialité, la transparence absolue des frais et la non-monétisation des données personnelles.

*Note : Aegis Bank et Namcod sont des entités fictives créées dans le cadre d'un exercice pédagogique de développement web.*

## Pourquoi ce projet est utile

Cette landing page répond à un cahier des charges strict alliant objectifs marketing et contraintes techniques :

- **Expérience Mobile "Zero-Scroll"** : L'interface mobile est conçue pour tenir sur une hauteur de vue unique (`100vh`), s'adaptant dynamiquement à l'écran de l'utilisateur sans aucun défilement vertical.
- **Architecture de l'information** : Une barre de navigation Desktop avec 5 liens fonctionnels (dont "Solutions Streamers" et "Financement Créatifs") et un menu burger sur mobile.
- **Hero Section Impactante** : Intégration d'un appel à l'action clair ("Télécharger l'app"), d'une offre promotionnelle de 20€ et de liens vers des réseaux sociaux alternatifs (Telegram, Mastodon, BlueSky) via des icônes SVG.
- **Transparence et Éthique** : Un design épuré qui reflète les valeurs de la banque, incluant un footer avec les mentions légales obligatoires.

## Comment démarrer

Ce projet est un site statique classique. Aucune installation complexe ou compilation n'est requise.

### Structure du projet

Le dépôt contient uniquement les fichiers essentiels :
- `index.html` : La structure principale et le contenu de la page.
- `style.css` : La feuille de style gérant le design responsive et le zero-scroll.
- `images/` : Le dossier contenant les ressources graphiques (logos, icônes SVG).

### Installation et utilisation

1. Clonez le dépôt sur votre machine :
   ```bash
   git clone https://github.com/votre-nom-utilisateur/aegis-bank-landing.git
   ```
2. Accédez au dossier du projet :
   ```bash
   cd aegis-bank-landing
   ```
3. Ouvrez simplement le fichier `index.html` dans votre navigateur web préféré (Chrome, Firefox, Safari) en double-cliquant dessus.
   
*Astuce pour les développeurs : Si vous utilisez VS Code, vous pouvez lancer l'extension "Live Server" pour bénéficier du rechargement automatique à chaque modification de votre code.*

## Où obtenir de l'aide

Si vous rencontrez des problèmes d'affichage (notamment sur la contrainte zero-scroll sur certains appareils mobiles) ou si vous avez des questions sur l'intégration :

- Ouvrez une **Issue** directement sur ce dépôt GitHub en décrivant le problème (taille de l'écran, navigateur utilisé).
- Vérifiez votre console navigateur (F12) pour vous assurer que les chemins vers le fichier `style.css` ou les icônes du dossier `images/` sont corrects.

## Mainteneurs et Contributions

Ce projet est développé et maintenu individuellement dans le cadre d'une formation professionnelle (simulée via l'agence Namcod). 

Les retours constructifs et les suggestions d'amélioration pour le design UI/UX sont les bienvenus. Si vous souhaitez proposer une modification :
1. Forkez le projet.
2. Créez une branche pour votre fonctionnalité (`git checkout -b feature/AmeliorationDesign`).
3. Poussez vos modifications (`git push origin feature/AmeliorationDesign`).
4. Ouvrez une Pull Request.

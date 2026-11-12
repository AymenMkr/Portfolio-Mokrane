# Portfolio — Mohamed Aymen Mokrane

Portfolio professionnel au design noir et vert néon, inspiré des terminaux.

## Démarrer

Ouvrir `index.html` dans un navigateur. Aucun paquet à installer ni compilation nécessaire.

Option avec serveur local :

```bash
python -m http.server 8000
```

Puis ouvrir http://localhost:8000.

## Fonctionnalités actuelles

- Design sombre noir et vert néon.
- Présentation de trois projets : agent de facturation, gestion logistique et chatbot Kidays.
- Détails de projets dépliables.
- Parcours de formation, dont anglais technique et professionnel en 2024–2025.
- Mise en page adaptée aux écrans mobiles.

## Technologies

HTML, CSS et JavaScript natifs. Les styles et le script sont regroupés dans `index.html`.

## État du projet

Première version du portfolio. Le téléchargement du CV, les liens de contact, les études de cas et la fonctionnalité IA du portfolio restent à intégrer. Le chatbot Kidays est un projet présenté, pas un assistant IA déjà intégré au site.

## Publier sur GitHub

1. Créer un dépôt vide nommé `portfolio-aymen` sur GitHub.
2. Extraire cette archive.
3. Dans le dépôt, cliquer sur **Add file → Upload files**.
4. Déposer le contenu du dossier `portfolio-aymen` (index.html et README.md à la racine).
5. Valider avec **Commit changes**.

### GitHub Pages

Dans **Settings → Pages**, choisir **Deploy from a branch**, branche **main**, dossier **/(root)**, puis **Save**. GitHub affichera le lien du site après déploiement.

### Alternative avec Git

Après création du dépôt vide, remplacer VOTRE_PSEUDO par votre identifiant :

```bash
git init
git add .
git commit -m "Première version du portfolio"
git branch -M main
git remote add origin https://github.com/VOTRE_PSEUDO/portfolio-aymen.git
git push -u origin main
```

## Développement à venir

- Ajouter CV, contact et liens GitHub/LinkedIn.
- Documenter les trois projets avec des résultats vérifiés.
- Intégrer une API IA via un backend, avec clé conservée côté serveur.
- Documenter le prompt système, les limites et au moins dix cas de test.

## Utilisation de l’IA

Cette première version a été réalisée avec l’aide de ChatGPT. Le code doit être relu, compris et adapté avant la soutenance.

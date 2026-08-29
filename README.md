# AYNEHA-CALENDRIER

Horloge et calendrier **PWA** (application web progressive) affichant l'heure, le jour, le
mois et l'année en direct, entièrement dans l'écriture **AYNEHA** - le système d'écriture
original créé pour transcrire la langue songhay, parlée au Mali, au Niger, au Burkina Faso
et au Bénin.

Conçu par **Mahamadou Issiaka MAIGA**, dit **MAIGUS**.

🔗 Site officiel du projet AYNEHA : https://ayneha-songhay.github.io/
🔗 Cette application en ligne : *(ajoute ici le lien une fois publié via GitHub Pages)*

## Fonctionnalités

- **Horloge en direct** (heures : minutes : secondes) en glyphes AYNEHA
- **Calendrier navigable** (mois précédent / suivant) avec le jour du jour mis en évidence
- **Jour, mois et année** affichés en écriture AYNEHA, sens de lecture droite-à-gauche
- **Année songhay** calculée automatiquement (année grégorienne + 2001)
- **Aucun caractère latin** : tout le contenu affiché est en glyphes AYNEHA (U+E000-U+E061)
- **Installable** sur l'écran d'accueil Android et iOS ("Ajouter à l'écran d'accueil")
- **Fonctionne hors connexion** grâce au service worker
- **Adaptatif** : bascule automatiquement entre les dispositions paysage et portrait selon
  l'orientation réelle de l'écran

## Structure

```
ayneha-calendrier/
├── index.html          # L'application (horloge + calendrier)
├── manifest.json        # Manifeste PWA (nom, icônes, couleurs)
├── service-worker.js    # Mise en cache pour le fonctionnement hors-ligne
├── ayneha_regular.ttf   # Police AYNEHA (glyphes U+E000-U+E061)
└── icons/                # Icônes de l'application (192px, 512px, versions maskable)
```

## Installation sur smartphone

1. Ouvrir le lien de l'application dans le navigateur du téléphone (Chrome sur Android,
   Safari sur iOS).
2. Utiliser le menu du navigateur puis choisir **"Ajouter à l'écran d'accueil"**
   (ou **"Installer l'application"** si la proposition apparaît automatiquement).
3. L'icône Horloge AYNEHA apparaît alors sur l'écran d'accueil, comme une application native.

## Hébergement

Ce dépôt est conçu pour être publié directement via **GitHub Pages** :

1. Aller dans **Settings → Pages** du dépôt.
2. Choisir la branche `main` et le dossier racine (`/`).
3. Enregistrer - le site est alors accessible à l'adresse fournie par GitHub.

## Licence / crédits

- Alphabet et police AYNEHA : © Mahamadou Issiaka MAIGA (MAIGUS)
- Icône de l'application : Icons8

© 2026 AYNEHA - Mahamadou Issiaka MAIGA (MAIGUS)

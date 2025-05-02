# ElecTracker - Site Web de Distribution

Ce dossier contient un site web simple pour distribuer l'APK de l'application ElecTracker à vos collègues.

## Structure des Fichiers

```
ElecTracker-Website/
│
├── css/
│   └── styles.css          # Styles du site
│
├── js/
│   └── script.js           # Fonctionnalités JavaScript
│
├── images/
│   ├── logo.png            # Logo de l'application (à ajouter)
│   └── app-showcase.png    # Capture d'écran de l'application (à ajouter)
│
├── downloads/
│   └── ElecTracker.apk     # Fichier APK de l'application (à ajouter)
│
└── index.html              # Page d'accueil du site
```

## Instructions d'Utilisation

1. **Ajoutez les fichiers manquants**:
   - Placez le logo de l'application dans `images/logo.png`
   - Ajoutez une capture d'écran de l'application dans `images/app-showcase.png`
   - Copiez le fichier APK de votre application dans `downloads/ElecTracker.apk`

2. **Personnalisez le site** (optionnel):
   - Modifiez `index.html` pour ajuster le contenu selon vos besoins
   - Ajustez les styles dans `css/styles.css` si nécessaire

3. **Déployez le site**:
   - Hébergez les fichiers sur un serveur web
   - Ou partagez le dossier via un réseau local

## Génération de l'APK

Pour générer l'APK de votre application ElecTracker:

1. Ouvrez votre projet dans Android Studio
2. Sélectionnez `Build > Build Bundle(s) / APK(s) > Build APK(s)`
3. Une fois la génération terminée, cliquez sur "locate" pour trouver le fichier APK
4. Copiez ce fichier APK dans le dossier `downloads/` de ce site web

## Notes Importantes

- Assurez-vous que vos collègues activent l'option "Sources inconnues" dans les paramètres de sécurité de leur appareil Android avant d'installer l'APK
- Ce site est conçu pour une distribution interne et n'est pas destiné à une utilisation publique
- Les couleurs du site correspondent à la palette de couleurs de l'application ElecTracker

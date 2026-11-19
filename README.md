# Geodesie APK

## Structure du dépôt
```
.github/workflows/build-apk.yml
www/index.html            ← l'application (AR / FR / EN)
resources/                ← icône (SVG + PNG Android)
capacitor.config.json
package.json
.gitignore
```

## Étapes
1. Crée un dépôt GitHub et envoie tout le contenu de ce dossier (y compris `.github/`).
2. Onglet Actions → Build APK → attends la fin (3-6 min).
3. Télécharge **Geodesie-APK** dans Artifacts (il contient app-debug.apk).

## Notes
- Le nom de l'app sur Android est fixe : Geodesie (le sélecteur de langue ne change que l'interface).
- Plugins natifs utilisés : Share et Filesystem (partage et export PDF).
- Les projets et l'historique sont stockés sur l'appareil (localStorage).

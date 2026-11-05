# EBC Toolbox 🍺

Calculateur de couleur EBC (formule de Morey) et densité initiale estimée pour le design de recettes de bière.
Une page HTML unique dans une WebView Android, compilée en APK par GitHub Actions.

## Fonctions

- Brassin : volume après ébullition (défaut 23 L) + rendement (défaut 75 %)
- Malts : bibliothèque fusionnée (stock + liste), recherche au clavier, EBC auto, kilos ±0,5, contribution en % de la couleur
- ÉBC bière (Morey) + OG estimée
- Bandeau coloré : le fond prend la couleur attendue de la bière
- Échelle des couleurs (0–80 EBC, vraies couleurs) + zones (Pâle, Dorée, Ambrée, Brune, Noire)
- 27 familles de styles en lanes colorées, recherche de style, styles compatibles dans le bandeau

## APK

Onglet **Actions** du dépôt → run **Build APK** → artefact **MiniApp-APK** (`app-debug.apk`).
Installer en autorisant « sources inconnues » ; mise à jour par remplacement de l'APK.

## Modifier

Éditer `app/src/main/assets/index.html` et pousser : recompilation automatique (~5 min).

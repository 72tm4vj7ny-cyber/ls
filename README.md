# CHERRY LINE — correctif complet (dossier `Media/` avec M majuscule)

Ce ZIP remplace uniquement les trois fichiers du site : `app.js`, `index.html` et `styles.css`. Il ne contient pas le dossier de médias : garde ton dossier GitHub `Media/` et tous ses fichiers tels quels.

Corrections incluses :
- toutes les références de médias utilisent `Media/` avec M majuscule, conformément au dépôt ;
- suppression forcée de la grille décorative ;
- Women2Women utilise l’intégration YouTube `Qc660Zu_hZI` en paysage 16:9 ;
- Sport Content 3 utilise l’intégration TikTok pour la vidéo `7646470778187222304`, en portrait 9:16, avec un lien direct de secours ;
- les vidéos locales continuent d’utiliser leurs chemins et noms de fichiers existants.

## Installation
1. Décompresse le ZIP.
2. Dans ton dépôt GitHub existant, remplace `app.js`, `index.html` et `styles.css` par ceux du dossier.
3. Ne remplace pas et ne renomme pas le dossier `Media/`.
4. Commit/push les changements et attends la publication GitHub Pages. Recharge ensuite le site en forçant l’actualisation.

## Vérifications et limite
La syntaxe JavaScript est vérifiée et les chemins de médias du code utilisent `Media/`. Le ZIP ne contient pas les fichiers médias. La lecture d’un embed TikTok dépend aussi du service TikTok et de ses autorisations ; si TikTok refuse l’intégration, le lien de secours ouvre la vidéo d’origine. Je n’ai pas prétendu avoir testé le site dans un navigateur réel.

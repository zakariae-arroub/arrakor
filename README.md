# ARRAKOR

Page de l'équipe **ARRAKOR**, équipe n°1 du challenge **Game of Robots 2026** (Polytech Angers, du 14 au 18 décembre 2026).

**Page en ligne :** https://zakariae-arroub.github.io/arrakor/

Instagram : [@arra_kor](https://www.instagram.com/arra_kor/)

## Contenu

| Fichier | Rôle |
| --- | --- |
| `index.html` | Toute la page : structure, styles et scripts (compte à rebours, poussière dorée). |
| `mascotte.html` | La mascotte animée : elle présente la mission, le rover, la méthode, l'équipage, le challenge et les partenaires, sujet par sujet ou en visite guidée. Affichée dans la section « La mascotte » de la page, et consultable seule en plein écran. |

Aucun outil de build : GitHub Pages sert les fichiers tels quels depuis la branche `main`. Les polices de la charte (Michroma pour les titres, Inter pour le texte, JetBrains Mono pour les chiffres) sont chargées depuis Google Fonts.

## Modifier la page

- **Textes** : ouvrir `index.html`, chercher la phrase à changer, enregistrer.
- **Couleurs** : les jetons de la charte ARRAKOR sont au début de la balise `<style>` (`--gold`, `--amber`, `--spice`…).
- **Compte à rebours** : la date de début est dans le script en bas de page (`START`).
- **Mascotte** : ses répliques sont au début du script de `mascotte.html` (`PRESENTATION`, `BRAVOS`). Les fiches qu'elle présente sont juste après : `EQUIPE` pour les membres, `SUJETS` pour chaque sujet (le champ `dit` est la phrase prononcée). `DICTION` règle la prononciation d'un mot sans changer son écriture.

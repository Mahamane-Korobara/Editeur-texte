demo : https://mahamane-korobara.github.io/Editeur-texte/
# Editeur de texte

Ce projet est un éditeur de texte web simple, permettant de formater du texte, d’insérer des listes, des liens, de choisir la police, la taille, la couleur, et d’appliquer différents styles (gras, italique, souligné, barré, exposant, indice, etc.). Il propose également des options d’alignement, d’indentation et de titres.

## Structure du projet

- [`index.html`](index.html) : Structure principale de l’éditeur, avec tous les boutons et options de formatage.
- [`style.css`](style.css) : Styles pour l’éditeur, les boutons, les listes déroulantes, la zone de texte et l’impression.
- [`script.js`](script.js) : Logique JavaScript pour gérer les interactions, appliquer les styles et mettre à jour l’état des boutons.
- [`.vscode/settings.json`](.vscode/settings.json) : Configuration pour Live Server (port 5502).

## Fonctionnalités

- **Formatage du texte** : Gras, italique, souligné, barré, exposant, indice.
- **Listes** : Ordonnée et non ordonnée.
- **Annulation/Rétablissement** : Undo/Redo.
- **Liens** : Ajouter ou supprimer un lien.
- **Alignement** : Gauche, centre, droite, justifié.
- **Indentation** : Augmenter ou diminuer l’indentation.
- **Titres** : Choix du format (paragraphe, H1-H6).
- **Police et taille** : Sélection de la police et de la taille du texte.
- **Couleurs** : Couleur du texte et du fond.
- **Impression** : Styles adaptés pour l’impression.

## Utilisation

1. Ouvre le projet dans VS Code.
2. Lance le serveur Live Server sur le port 5502.
3. Accède à l’éditeur via ton navigateur.
4. Utilise les boutons et options pour formater ton texte dans la zone principale.

## Personnalisation

- Ajoute des polices dans la variable `fontListe` de [`script.js`](script.js).
- Modifie les styles dans [`style.css`](style.css) selon tes préférences.

## Auteurs

- Projet réalisé par Mahamane

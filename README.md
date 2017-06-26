# Test SEPPA : développeur back-end

- Principe du test : Traitement (import — export) d'un lot de données en JSON.
- Langage : PHP ou JS ou les 2 !

## Taches principales :

**NOTE:** vous êtes libres d'utiliser le framework et/ou bilbiothèque de votre choix. Un bonus pour en justifier le choix.


1. Objet JSON, source et préparation :
  - Les clés du JSON à utiliser sont : Update, SyndicObjectName, EQUIP, OUVERTURE
  - Ainsi : les colonnes du tableau dans lequel afficher les données seront nommés : "Publication", "Nom", "Equipements", "Ouverture"
  
2. Affichage des données
  - La colonne "Publication" affichera une date au format fr (jour mois année), tel que : "Mis à jour il y a ... jour  
  - La colonne "Equipements" aura son contenu affiché sous forme d'une liste chaque élement
  - La colonne "Ouverture" devra afficher une date de début / date de fin sous la forme "Ouvert du (jour mois) au (jour mois)".
    **NOTE :** Le contenu de cette clé possède une date de début sous la forme JJ/MM/YYY et une date de fin sous le même format.
    - Afficher "Ouvert toute l'année" si les dates traitées vont du 1er janv. au 31 dec.
  - Une colonne "case à cocher" servira à sélectionner une ligne et exporter les données
  
3. Export des données
  - Chaque ligne du tableau possède une checkbox : à  la soumission du formulaire, on exporte dans un nouveau JSON les elements cochés
  
## Additional Instructions

- Déposer le lien vers votre travail sur un répertoire de votre choix (github/bitbucket/codepen...)
- Laissez votre code commenté (s'il y a des interrogations, points incomplets)

## Bonus Points

- Test
- Code indenté
- Faire simple ! Emploi de bonnes pratiques / code patterns.


- Principe de l'app : Traitement (import — export) d'un lot de données en JSON 
- Langage : PHP ou JS ou les 2 !


EXPORT DE LA SÉLECTION :
• Chaque ligne du tableau possède une checkbox : à  la soumission du formulaire, on exporte dans un nouveau JSON les elements cochés.

Le tout est que ça reste lisible, qu’il y ait un bon traitement de l'information source et un l’aspect simple de l’export.

Ci-joint le JSON volontairement laissé tel quel,
N’hésites pas si tu as des questions,

D’avance merci,
Benoit


# Test SEPPA : développeur back-end

Dear candidate, please follow this readme and solve all questions.

> Before you can start, you should prepare your development environment.

## Taches principales :

**NOTE:** vous êtes libres d'utiliser le framework et/ou bilbiothèque de votre choix. Un bonus pour en justifier le choix. PHP, JS peu importe.

Parsing JSON, affichage des résultats dans un tableau puis export des données sélectionnées vers un nouveau JSON.

1. JSON
  - Créer un tableau et y afficher chaque objet JSON
  - Les clés du JSON à utiliser sont : Update, SyndicObjectName, EQUIP, OUVERTURE
  - Ainsi : les colonnes du tableau seront nommés : "Publication", "Nom", "Equipements", "Ouverture"
  
2. Affichage des données dans un tableau
  - La colonne "Publication" affichera une date au format fr (jour mois année), tel que : "Mis à jour il y a ... jour  
  - La colonne "Equipements" aura son contenu affiché sous forme d'une liste chaque élement
  - La colonne "Ouverture" devra afficher une date de début / date de fin sous la forme "Ouvert du (jour mois) au (jour mois)".
    **NOTE :** afficher "Ouvert toute l'année" si les dates traitées vont du 1er janv. au 31 dec.
  - Une colonne "case à cocher" servira à sélectionner une ligne et exporter les données
  
3. Traiement des données
  - Chaque ligne du tableau possède une checkbox : à  la soumission du formulaire, on exporte dans un nouveau JSON les elements cochés
  - response contains count of Near-Earth Objects (NEOs)
  - persist the values in your DB
  - Define the model as follows:
    - date
    - reference (neo_reference_id)
    - name
    - speed (kilometers_per_hour)
    - is hazardous (is_potentially_hazardous_asteroid)

  
## Additional Instructions

- After you're done, provide us the link to your repository.
- Leave comments where you were not sure how to properly proceed.

## Bonus Points

- Test
- Code nettoyé
- Emploi des bonnes pratiques / code patterns.

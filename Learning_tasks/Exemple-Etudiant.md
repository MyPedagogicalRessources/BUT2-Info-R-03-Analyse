# Dictionnaire de Données

| Nom | Description | Type | Contraintes | Règles de composition/calcul |
| --- | --- | --- | --- | --- |
| Utilisateur | un utilisateur du site peut importe son rôle | Entité |  |  |
| Visiteur | un visiteur du site | Entité |  |  |
| Membre | visiteur authentifié du site | Entité |  |  |
| nom | Nom du membre | Chaine de caractère | Non null  et non vide |  |
| prénom | Prénom du membre | Chaine de caractère | Non null  et non vide |  |
| adresseElectronique | adresse électronique du membre | Chaine de caractère | Non null  et non vide |  |
| privilege | Droit du membre sur les actions du site | Chaine de caractère | Non null  et non vide |  |
| Membre expert | visiteur authentifié du site | Entité |  |  |
| Administrateur | administrateur du site | Entité |  |  |
| Evènement  | un évènement du site | Entité |  |  |
| titre | titre de l’évènement | Chaine  de caractère | Non null  et non vide |  |
| date | date de l’évènement | Date | Non null  et non vide |  |
| lieu | lieu de l’évènement | Chaine de caractère | Non null  et non vide |  |
| info | informations supplémentaire de l’évènement | Chaine de caractère |  |  |
| personneInscrite | personne qui sont inscrites à l’évènement | Tableau d’Utilisateur |  |  |
| Article | un article du site | Entité |  |  |
| titre | Titre de l’article | Chaine de caractère | Non null  et non vide |  |
| description | Description de l’article | Chaine de caractère |  |  |
| texte | Contenu de l’article | Chaine de caractère | Non null et non vide |  |
| catégorie | Catégorie de l’article | Chaine de caractère |  |  |
| Message d’erreur | message d’erreur pour une action | Chaine de caractère | Non null et non vide |  |
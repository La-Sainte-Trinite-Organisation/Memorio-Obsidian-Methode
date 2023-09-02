---
tags:
  - Type/note
aliases:
  - Normes & Standards pour Obsidian
lead: Lead paragraph goes here
visual: 
Z-UUID: "2023090118464056"
Date de création: 2023-09-01 18:45
Date dernière modification: 2023-09-02 16:12
---

> [!Note] Seulement à titre indicatif
>Le but principal de cette note est de fournir un moyen et une piste à suivre pour que vos notes puissent être retrouvées dans 20 ou 30 ans
# 1. Convention sur les noms de fichiers

<!-- Main content of my thoughts really -->
## 1.2 Z-UUID
Comme vous avez pu le voir, depuis les dernières versions de ce coffre, un identifiant unique à été ajouté à chaque note. Cette identifiant de format YYYYMMDDHHmmssSS (Année, Mois, Jour, Heure, Minute, Seconde, Millisecondes)(format de date ISO), ajouté dans les métadonnées et dans le tire des notes permettra de les retrouver (retrouver les liens et connections) dans 20 ou 30 ans, et ce même si le titre de la note change. Il faut voir cet identifiant comme l’emprinte digitale de votre note : même si la note change de vêtement, sont empreinte digitale reste la même.

A l’heure actuelle, j’ai essayé de rendre ce coffre le plus automatisé et intuitif possible, cependant, je n’ai pas trouvé de solution pour ajouter l’UUID de la note (l’emprinte digitale), à la fois dans le titre de celle ci et dans les métadonnées sans avoir de conflit d’ID, par conséquent, à la création d’une nouvelle note, voici ce que vous devrez faire : 
1. Créer une nouvelle note
2. Insérer n’importe quel modèle (template) (via le core plugin “Modèle” (Ctrl + P → Modèle → insérer un modèle))
3. Copier la valeur affiché dans la propriété “Z-UUID”
4. Coller cette valeur au format : {{Titre de la note en lettre}} - {{Z-UUID}}
5. (Optionnel) : Si vous voulez que Obsidian vous propose automatiquement des connections possible, copiez/collez le {{Titre de la note en lettre}} dans la propriété intitulé “aliases” de la note (si la propriété n’existe pas, crez là via le bouton en haut “Add property” ou directement dans les métadonnées YAML en passant par la vue “source”)
## 1.3 Nommage des fichiers
Pour retrouver plus facilement vos fichiers, vous pouvez inclure plus de contexte dans les noms de vos fichiers

Ainsi, une note de cours Cornell passerai de ça : “La Révolution Française - {{Z-UUID}}” à “La Révolution Française - Cours Cornell - {{Z-UUID}}”
Vous pouvez ajouter la date, mais étant donnée que le Z-UUID est basé sur la date ça n’a pas spécialement d’intéret.

# 2. Formats
## 2.1 Format de date
Pour les dates, dans un esprit long terme, je me suis appuyé sur la norme ISO 8601, un standard international de date qui ce défini comme suit : 
YYYY-MM-DD (HH:mm:ss.SS) ou en français Année-Mois-Jour (Heure:minute:secondes.milisecondes). L’intéret de placer les années en premier, à l’inverse du français, est de permettre un tri des fichiers nommé avec des dates d’être trié comme dans un entonnoir, avec d’abord un tri par année, puis par mois, puis par jour etc…

# 3. Tags
Les tags sont utilisés afin de créer des dossiers et sous dossiers infinis. Le tout en permettant d’avoir différents fichiers stockés dans plusieurs tags-dossiers. Ainsi lors de la recherche d’une note il devient facile de la retrouvé grâce à ces tags, mais aussi de la catégoriser.
**<u>Liste des tags</u>** : 
- 



---
## Questions
<!-- What remains for you to consider? --> 
- 

## Terms
<!-- Links to definition pages -->
- 

## References
<!-- Links to pages not referenced in the content -->
- 
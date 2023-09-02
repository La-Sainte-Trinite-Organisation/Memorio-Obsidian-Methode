---
sticker: vault//4 RESSOURCES/Pièces Jointes/Illustrations/Obsidian logo.svg
Date de création: 2023-08-18 12:08
Date dernière modification: 2023-08-30 20:14
---
# 0.) Description
Note servant à ranger tout les tests fructueux faits avec leur description et utilité
# 1.) Ajout de lien automatique vers notes quotidiennes

1. Commande : [[3 CASQUETTES/°Life tracking/Notes quotidiennes/{{date:YYYY/MM/DD}}|{{date:YYYY-MM-DD}}]]
2. Utilité : Sert à linker automatiquement la nouvelle note crée à partir d’un model à une note quotidienne
# 2.) Rangement auto de notes quotidiennes
1. Commande : {{date:YYYY/MM/DD}}
2. Utilité : Format de titre des notes quotidiennes, permet de créer les dossiers manquants à la création des notes quotidiennes et de les ranger par Années > Mois > Jours (utilisation de la notation anglaise qui ma fois et plus logique)
# 3.) Catégorisation des tags
1. Commande : #tags/tag1/tag1/tag1/tag1/tag11
2. Utilité : Étant donnée que les tags sont des dossiers infini, ça permet de créer des sous dossiers avec des tags
# 4.) Copie/Sync auto des métadataq
J’avais besoin de trouver un moyen de copier les métadata YAML dans ma partie métadata au niveau du fichier, pour les liens etc, du coup, j'ai fait ça : 
1. YAML : Date de création : "{{date:YYYY/MM/DD}}"
	1. Utilisation des variables natives du core plugin “Modèles”
2. Mes métadatas : [[3 CASQUETTES/°Life tracking/Notes quotidiennes/<% tp.frontmatter["Date de création"] %>|{{date:YYYY-MM-DD}}]]
	1. Ici utilisation des variables templater
# 5. Date de modification manuelle
Pas le choix, j’ai pas réussi à faire fonctionner les templates dynamiques templater
Commande : [[3 CASQUETTES/°Life tracking/Notes quotidiennes/Insérer la date de modification format YYYY/MM/DD|Insérer la date de modification format YYYY/MM/DD]]
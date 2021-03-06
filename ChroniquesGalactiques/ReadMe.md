# Chroniques Galactiques

_A french Scifi RPG based on the D20 system / OGL 3.5._

Chroniques Galactiques est un jeu de r&ocirc;le futuriste complet bas&eacute; sur le syst&egrave;me d20/OGL 3.5.

Cette feuilles de personnage inclue quelques jets et r&egrave;gles optionnelles.

Le jeu complet est paru dans le magazine [Casus Belli](http://www.black-book-editions.fr/catalogue.php?id=207) #17,18 et 19.

# Version courante
3.4 [Screenshot](cog_v3.png)

# Notes de version
## V3.4 (2019-01-02)
### Fiche de PJ
* Plus de cases Traits/Divers sur l'onglet Caractéristiques. Ces informations peuvent être indiquées dans la liste répétable des traits de l'onglet Capacités (un sheet-worker de MAJ de version importe l'ancienne valeur du champ Traits)
* Ajout d'un sheet-worker permettant de détecter si le personnage a subi une blessure grave, quand il perd en une seule fois un nombre de PV supérieur au seuil. La case Blessure est automatiquement cochée et l'état préjudiciable Affaibli activé.
* Les Traits sur l'onglet Capacités sont maintenant affichés en permanence
* Ajout de cases à cocher sur les lignes d'armes/attaques permettant de faire un jet d'attaque sans jet de dommages ou un jet de dommages sans jet d'attaque
* Ajout d'une option Choix dans les Mods et Mods de test des jets de capacités permettant de choisir la caractéristique à utiliser au moment du jet

### Fiche de PNJ
* Ajout de cases à cocher sur les lignes d'armes/attaques permettant de faire un jet d'attaque sans jet de dommages ou un jet de dommages sans jet d'attaque (fiches PJ et PNJ)
* Import du Statblock sur l'onglet Caractéristiques de la fiche PNJ
* Amélioration de la fonction d'import de statblock pour permettre la création d'une ligne d'attaque sans attaque ou sans dommages (la présence du mot DM sur la ligne d'attaque reste nécessaire pour qu'elle soit reconnue en tant que telle)

### Fiche de vaisseau
* Ajout d'un sheet-worker permettant de remplacer les " dans le nom du personnage par des «» (évite des problèmes de parsing dans les macros)
* Modification des postes d'équipage, avec un champ permettant d'indiquer le nom du personnage et son rang dans sa spécialité (Pilotage, Moteurs, Electronique, etc...)
* Modification des options des lignes d'armes pour pouvoir indiquer le nom du canonnier et son rang en Armes lourdes
* Ajout de sheet-workers pour convertir les noms & rangs des PJs aux postes d'équipage en syntaxe utilisable dans les macros de tests et d'attaques

### Roll Template
* Modification cosmétique avec une bordure aux coins arrondis et un affichage élargi
* Nouveau tag {{portee= }} permettant d'afficher la portée d'une arme à distance
* Modification pour permettre l'affichage d'un jet de dommages même sans jet d'attaque préalable

## v3.3 (2018-12-20)
* Réorganisation de la fiche en 3 onglets principaux : 
 * Personnage avec 4 sous-onglets : Caractéristiques (+attaques), Capacités (voies, et autres traits), Equipement, Configuration (et buffs)
 * Vaisseau avec 2 sous-onglets : Caractéristiques (+attaques), Configuration (et buffs)
 * PNJ avec 2 sous-onglets : Caractéristiques (+attaques), Configuration

* L'onglet Configuration de la fiche de PNJ comporte un champ permettant de copier un statblock depuis un document PDF. Voir le Wiki pour plus d'information.

## v3.2 (2018-12-11)
* Ajout de la section répétable des "Autres traits" avec un bouton d'affichage murmuré dans le chat
* Corrections et ajustements divers (typo, erreurs de noms d'attributs, espaces surnuméraires dans les macros)
* Ajout d'une classe de bouton 'output' représenté par une bulle d'aide
* Ajout d'une classe d'affichage 'text' pour utilisation dans le roll template (texte sans limite de scrolling, avec police à 90%, en italique et justifié)

## v3.1 (2018-12-03)
* Ajout du d3 au selecteur des dés de dommages
* Ajout d'un groupe de dés de dommages "sans limite" (armes à feu)
* Ajout de deux options d'attaque sur la deuxième ligne : relance (reroll et reroll once) et seuil de relance (à indiquer sous la forme  d'un seuil -- relance des 1 par défaut).
* Réorganisation de la section Etats préjudiciables
* Ajout d'un état "Poisse" consistant à lancer deux d20 et garder le moins bon
* Modification des jets de dés de la fiche pour tenir compte de l'état "Poisse"
 Type des jets avec poisse :
 * Jet de carac normal : moins bon de deux d20 (au lieu d'un d20)
 * Jet de carac supérieur OU héroïque : un seul d20 (au lieu du meilleur de deux d20)
 * Jet de carac supérieur ET héroïque : meilleur de deux d20 (pas de minimum à 10)
 * Jet d'attaque normal : moins bon de deux d20 (au lieu d'un d20)
 * Jet d'attaque risqué : moins bon de deux d12 (au lieu d'un d12)
 * Jet d'attaque expert : un seul d20 (au lieu du meilleur de deux d20)

## v3.0 (2018-11-29)
* Réorganisation de la fiche de personnage avec des onglets Caractéristiques, Capacités, Equipement, Configuration
* Remplacement des champs Divers sur les attributs par des champs calculés via sheet-workers
* Affichage des options d'attaque avec pictogramme d'engrenage
* Affichage jusqu'à 9 voies
* Gestion de 5 buffs/debuffs par attributs
* Support des états préjudiciables aveuglé/étourdi/renversé/surpris avec pénalités aux attributs correspondants
* Ajout d'un onglet Vaisseau avec attributs et jets de dés spécifiques aux vaisseaux spatiaux

## v2.0 (2018-10-23)
* Prise en compte des caractéristiques supérieures et héroïques
* État affaibli ou normal
* Bouton pour signaler une initiative variable
* Bouton pour faire les jets en caché (utile pour les PNJs)
* Correction de l'utilisation de SAG par PER dans les jets de capacité
* Réorganisation des attaques, avec 
 * champs pour le nom de l'attaque, 
 * les attaques risquées et expert,
 * les seuils d'incident de tir, 
 * la possibilité de tir visé,
 * et tir en haute-capacité.
* Correction dans les attaques : magie est remplacé par psy
* Amélioration des roll templates
* Tranformation de la zone de texte équipement personnel en section répétable
* Ajout d'une zone d'équipements divers

## v1.3 (2017-10-02)

* Jets d'arme : la propriété spéciale est affichée dans le chat (permettant d'ajouter des jets avec "[[1d6+2]] dégâts de feu" par exemple)

## v1.2 (2017-09-17)

* Correction : les caractéristiques au-dessus de 30 ne provoquent plus de message d'avertissement

## v1.1 (2016-07-13)

* Ajout d'une section répétable de jets paramétrables (+description) dans la section Capacités (Voies)

## v1.0 (2016-07-11)

Création de la feuille.

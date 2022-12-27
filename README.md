# Documentation du produit -clause-sociale-

## Contexte 
La zone est un regroupement de coopératives qui se partagent le portage de Startup-d'État au sein du marché inter-ministériel *21BAM048 - "Réalisation de services publics numériques en mode produit coordonnés par le programme interministériel Beta.gouv"*.

Devant la pluralité de fonctionnement des structures et des manières de réaliser le portage, plusieurs personnes de la zone ont proposé de regarder ensemble la pertinence de dévélopper / mutualiser les outils

Un premier temps a été consacré à réaliser des ateliers, réunions collectives et entretiens afin de comprendre les attentes et besoins des différentes coopératives, ainsi que leurs pratiques et leurs usages dans la gestion des Startup-d’Etat.

Les personnes qui ont réalisés ces entretiens y ont vu des opportunités de développer des outils qui permettraientt de suivre :
- les échange avec les administrations ;
- la clause sociale ;
- le portage d'une SE.
    
Désirant réduire le scope, elles ont proposés de démarrer sur le projet de la Clause sociale.

### La clause sociale 
La clause sociale est une disposition prévue par le code de la commande publique pour favoriser l'insertion sociale et professionnelle des personnes en situation de handicap ou défavorisées. Dans le marché inter-ministérielle qui réunit -la zone- l'acheteur a décider d'inclure ce dispositif.

Les attributaires de -la zone- sont tenu de reverser **1h d’insertion à réaliser par tranche de 2 000 euros facturée**
*source : [CCAP-21BAM-048 - 1.4](CCAP-21_BAM_048.pdf)*

La redevabilité pourrait être par structure, mais dans la réalité c'est tout le groupement qui est solidairement redevable de l'obligation de la clause sociale auprès de l'EPEC. Dans les faits, il y a des structures qui embauchent, d'autres qui n'embauchent pas et l'obligation de la clause sociale passe par une redistribution de la dette entres les structures.

## la Vision
### Les problèmes
- les structures ne doivent pas les mêmes montants, il faut donc calculer qui doit combien à la clause soxiale
- certaines structures choisissent de laisser la gestion de l'obligation de la clause sociale à d'autres structures, donc c'est complexe de calculer la redistribution de la dette entre les structures
- les structures qui désirent embaucher n'arrivent pas à savoir combien il faudrait d'argent pour embaucher quelqu'un
- le groupement doit des comptes à l'EPEC et à Betagouv et c'est difficile de leur fournir les données à jour
- les personnes embauchées ne savent pas combien elles coûtent à l'entreprise

### Solutions (les principales fonctionnalités)
Une [google sheet](https://docs.google.com/spreadsheets/d/1Y0zEqkP8VTm2KTSqYvhoO0aZvxqEuulqqONt3UXXmOc/edit#gid=0) à a été construit pour permettre le suivi de la clause sociale.
Les "user stories" auxquelles il répond sont listé [dans ce document](https://github.com/clause-sociale/documentation/blob/main/specificationsv0.md)

### à qui le produit est destiné
- à Béatrice de l'EPEC et à Ishan de Betagouv
- aux personnes dans les structures du groupement qui sont impliquées dans la gestion financière des SE
- aux personnes embauchées (Pauline, Liam et Anse)

## Artefacts
  - Tout savoir sur l'équipe ([lien](équipe.md))
  - Lien vers l'outil [lien](https://docs.google.com/spreadsheets/d/1Y0zEqkP8VTm2KTSqYvhoO0aZvxqEuulqqONt3UXXmOc/edit#gid=1671905186)
  - Backlog ([lien](https://github.com/orgs/clause-sociale/projects/1))
  - Release plan / roadmap
  - Lien vers le prototype ([lien](https://docs.google.com/spreadsheets/d/1DTjqb3i5K2uoPJp0A_wgbt3e7QXxmQUVB6rJRR0IEGk/edit#gid=130128679))
  - Suivi budget / temps passé ([lien](https://github.com/clause-sociale/documentation/blob/main/letempsquipasse.md))


## Comment on aimerait travailler ?
- les personnes qui se proposent d’animer le projet proposent de faire attention à la manière de faire, d’essayer de ne pas reproduire des dysfonctions, impliquer tous les métiers, etc. s’accorder pour éviter le risque de faire le produit sans que tout le monde soit satisfait
- pour s'accorder rapidement entre nous décidons de partir sur du *scrum*
- de documenter

## Où en est le projet ?
Le projet a mené à la structuration du [google sheet](https://docs.google.com/spreadsheets/d/1Y0zEqkP8VTm2KTSqYvhoO0aZvxqEuulqqONt3UXXmOc/edit#gid=0) de suivi de la clause sociale.
Deux documents avait été créés en parallèle, l'un suivant les factures réelles émise à l'état, l'autre se basant sur les bons de commande émis pour estimation les heures de clauses sociales dûes et à devoir.
Au final, les deux solutions ont été intégrées sur un même documents. 
Les heures dûes sont calculées à partir des factures réellement émises, les heures dûes estimées sur une périodes sont calculées à partir des bons de commande.

A ce jour (26.12) il n'est pas prévu de pousser le développement à un application web.
Le tableau a été présenté aux membres de La Zone et semble convenir aux attentes actuelles.
Nous souhaiterions, dans un premier temps, utiliser ce document pour en observer les usages. 

## Licence
(en cours)

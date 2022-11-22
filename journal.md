# Journal
## 18 novembre 2022 - à propos de user story

Pntbr : 
J'ai l'impression que pour comprendre l'esprit des U.S. il faut revenir au truc d'avant les -Use Cases-
Les Uses Cases visait à spécifier, càd à décrire précisément et sous forme de scénarios les interactions entre les personnes utilisatrices et le système.
Par ex. pour un distributeurs de billets :
scénario nominal :
1- la personne insère sa CB
2- le système lui demande son code
3- la personne rentre un code à 4 chiffres
4- le système lui demande le montant
5- etc.
scénario alternatif - code erroné :
4a- le système demande à rentrer son code à nouveau
5a- etc.
--
C'était déjà beaucoup mieux que les spécifications monolithique d'avant, car on découpait le système en unité fonctionnelle et on pouvait faire des backlogs (avec des UC dedans) et imaginer construire le produit de manière itérative et incrémentale.
Intuitivement ça semblait être une bonne idée mais dans la réalité ça ne fonctionnait pas.
Plein de -jeux sérieux- sont apparus pour montrer pourquoi :
http://flenotre.github.io/article/draw-the-drawing-game/
--
La petite révolution des US, c'est qu'on ne cherche plus à spécifier par écrit, on souhaite partager en se racontant des histoires oralement.
Il peut y avoir très peu de chose dans une US, par exemple, le dessin d'un caddie pourrait suffire pour une US qui concernerait le panier d'un site de vente - (c'est ce que propose Gojko Adzic).
On peut utiliser les 3C qui décrivent le cycle de vie d'une US :
Card : faire une carte pour partager visuellement (PO)
Conversation : cette carte est une promesse de conversation avec l'équipe (Dev) pour clarifier ensemble tout au long de sa réalisation
Confirmation : on détermine ensemble ce qu'il faudrait pour que l'US soit terminée et on confirme ensemble qu'elle est terminée
--
On peut utiliser le pattern original des US : https://www.mountaingoatsoftware.com/agile/user-stories
Mais c'est un peu rigide et à mon avis inutile
J'imagine qu'un verbe d'action et un complément suffisent :
consulter les randonnées
afficher la fiche d'un randonneur
calculer un itinéraire

Sofia : 
Mes remarques / réflexions
Merci déjà pour une définition claire du concept de -Use Cases-
---
En revanche j’arrive pas à le raccrocher avec le concept des cas d’usages dont parlent certains coach chez Beta - c’est un problème de traduction ? de culture ?

Pntbr : 
J'imagine que peu de sujets sont aussi mal interprétés que la culture Agile.
Peut-être parce que c'est très teinté : connaissance empirique.
Ou bien parce que ça concerne, les PO, les dévs de manière assez périphérique.
Ou bien que beaucoup de personnes se sont retrouvées à en faire plus ou moins bien dans un contexte donné.
Souvent, j'ai l'impression que les personnes interprètent les -rétrospectives- ou les -Users Stories- ou -Scrum- à leur sauce sans s'être documentées ou avoir fait une formation sur le sujet.
(je me demande qui à part /ut7 à beta.gouv à une "bonne" connaissance des pratiques Agiles)
À l'époque on utilisait plutôt la traduction - cas d'utilisation que cas d'usage
Pour l'utilisation du terme cas d'usage à beta, je pense que c'est une libre interprétation du terme qui a été introduit quand Henri Verdier et Pierre Pezzardi installait le vocabulaire : startup d'état, état plateforme. le livre
Quelques liens :
https://fr.wikipedia.org/wiki/Cas_d%27utilisation
La bible : rediger-des-cas-d-utilisation-efficaces

Sofia : 
Puis merci aussi pour la définition des User Stories
Effectivement j’ai l’impression qu’il y a pleins d’écoles qui défendent chacune La meilleure la formulation - du coup j’aime bien l’idée de faire au plus simple et d’y associer les 3C - rien ne remplace une discussion
---
toutefois j’ai 2 questions :
- j’ai beaucoup entendu : “c’est important qu’une user stories soit validée par un vrai besoin d’une vraie personne”, par exemple : en tant que peut être future randonneuse, j’ai besoin de consulter les dates des randonnées pour savoir si il y a en une qui correspond à mes dispos
comment défendre le fait de faire plus simple ?
- à propos du 3e C = confirmation = ça peut prendre quelles formes ?

Pntbr : 
"c’est important qu’une user stories soit validée par un vrai besoin d’une vraie personne"
Oui, c'es cool comme point d'attention et le template :
En tant que <vraie personne> je veux <faire un truc> afin que mon <vrai besoin soit pris en compte>
rappel et adresse ça.
Mais, je trouve qu'il y a un côté grossier et un peu mécanique qui ne garantie pas que ce soit vraiment bien compris et pris en compte par l'équipe.
Par exemple, si l'équipe n'est pas débutante je préfère :
consulter les randonnées - et une conversation sur la valeur et la personne cachée derrière
plutôt que :
En tant que personne randonneuse je souhaite consulter les randonnées afin de choisir celle qui correspond le mieux à mes capacités ou mes envies

Pntbr : 
"à propos du 3e C = confirmation = ça peut prendre quelles formes ?"
Au départ au dos des cartes (bristol) de chaque US, pendant la Conversation on inscrivait les points de Confirmation. Dans une version simple.
US32 - Consulter les randonnées
et au dos :
doit afficher 10 randonnées par page (le reste est paginées)
doit afficher les randonnées par ordre alphabétique
doit afficher le titre, la distance et le temps estimé
Maintenant, j'inscrivais ça dans l'issue github ou gitlab
Et à ça on peut rajouter les contraintes du DoD (Definition of Done) qui s'adresse aux US pour que la Confirmation soit complète
Par exemple :
doit être déployée sur le serveur de staging
doit être consultable en FR et en EN
etc.
 


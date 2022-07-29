# Notes Nicolas

22 mars - scopopop

- à l'aise ? : pas de commentaire, j'avoue que j'ai manqué les points, et j'ai pas compris le périmètre. C'est l'occasion de comprendre.

Je pige pas le périmètre :
- modèle de gouvernance ?
- outils ?
- modèle de production ?

S: on essaye de comprendre le périmètre ?
N: Je comprends toujours pas pourquoi ?
N: J'ai l'impression que c'est pas clair, qu'est ce qu'on va faire ? Qui veut faire quoi ?


S: est-ce que tu en portes ?
N: on en porte 4 
S: et toi ?
N: On est 4, 2 sont mobilisés sur le marché, moi et johnatan. On part à 2 sur 6 mois
N: J'en porte 4 ou 0, en binome

S: est-ce que tu serais ok pour me lister les séquences ?
N: on a un doc, je sais plus où il est
N: on a drafter un process
N: j'essaye de te l'envoyer

N: expression de besoin
N: rédige le devis
N: on embarque les sous-traitant
N: je sais pas quoi te dire
N: on utilise Dolibar (on aurait pu utiliser Odoo)
N: c'est pas pratique et poussérieux
N: On a développé une surcouche
N: login par email (password less)
N: ielles mettent leurs factures
N: on voulait partir lowcode et en fait comme fallait gérer les stacks et l'infra ?

S: Qu'est-ce qui te manque ?
N: on a fait un truc en Node qui va écrire dans la DB de Dolibar
N: on a été choqué qu'un truc simple comme Bdc-facture n'existe pas dans les ERP
N: Zoo ERP on a regardé mais pas trouvé
N: après avoir benchmarké on a développé une appli node en 6 jours, c'est pas top mais ça remplit 90% de nos soucis
S: Provigis ?
N: Ce n'est pas un ERP, et ce n'est toujours pas automatique. Ils appellent et donc pas automatique.
N: On s'est posé la question de le prendre

S: pour gérer le cas d'usage : récupérer et payer les factures sous-traitants
N: on a drafté, les factures, budget, BdC
N: ce qui serait bien ce serait d'uniformiser tous les outils disparates des ministères : trello, notion, etc.
N: on peut partager la base de code

S: C'est quoi l'enjeu ?
N: En terme de workflow : Bdc Ok, Factures Ok (à voir), livrables SF et workflow, Chorus
N: Cette partie de livrable n'est pas dans le scop
N: On a juste la Dinum et la DGTM rien que c'est deux là, ce n'est ni les mêmes outils, ni les mêmes workflow
N: la DGTM dit que le workflow de la DINUM est plus cool et me demande de le dire à Benjamin
N: Je dis : débrouillez vous ;)
N: On court après les gens

S: facile et reloud ?
N: Facile : devis, facture (difficile)
N: Douleur : SF difficile, remplisse pas, signe pas
N: On est pas Octo, on a pas envie de s'enfermer dans des process et en même temps on en a besoin

S: Clause sociale ?
N: Hors-scope pour l'instant on a pas géré le truc
N: on a décidé de ne pas prendre et de mutualiser avec scopyleft
N: on devrait voir avec scopyleft
N: il faudrait que l'on se cale pour se synchroniser et partager
N: le partage d'info entre nous est peut-être difficile entre nous
N: [gros problème parce que chaque boite à son fonctionnement, ses outils, partager le même front office - Back office différent ?]
N: [c’est pas une condition sine qua non de construire ensemble - en revanche, qu’est-ce qu’on pourrait mutualiser entre nous ? Et comment ? un intranet ?]
N: encore un outil avec un google sheet
N: peut-être une API
N: peut-être biais de tech, mais c'est quand même sans doute automatisable
N: on s'est laissé 3 mois pour passer en mode 80/20 pour imaginer automatiser 80%
N: les factures c'est chronophage, et du coup c'est ça qu'on souhaitait automatiser
N: si on avait des reporting intra-zone
N: peut-être une API push/pull
N: notre démarche est de faire un truc pour automatiser
N: le prochain truc ce serait d'avoir un dashboard propre pour les intras [pour qu'ils puissent suivre où en est le budget]
N: et relance automatique pour les factures et service fait
N: et extérieur pour trello/notion - node-RED
N: je pense qu'il faudrait passer sur un mode open-source pour développer un truc [comment on itère ensemble sur des trucs existants?]
N: je veux pas avoir d'entrave, je veux répondre à mon cas d'usage, mais faut d'abord que ça réponde à mon cas d'usage
[N: merci de faire le lien]
N: https://n8n.io/




 















# Spécification v0
## Où en sommes-nous ?
Audrey et Sofia décident de marquer un arrêt, pour laisser les personnes utiliser le dernier fichier produit et voir ce qu'il en découle (retours, demandes d'amélioration, rien du tout, etc.)
- [Lien](https://docs.google.com/spreadsheets/d/1Y0zEqkP8VTm2KTSqYvhoO0aZvxqEuulqqONt3UXXmOc/edit#gid=1671905186) vers le tableur.

## Structuration de l'outil
### Onglet : participation et paiements de chaque structure
- **uses stories**
    - savoir qui doit combien à qui à un instant T
- comment ça marche ?
    - pour que les montants dus soient calculés, il faut renseigner les factures et les heures déclarées dans l'onglet "suivi des heures"
    - pour que les mouvements monétaire entre les structures soient calculés, il faut renseigner dans le tableau "Facturation HT par structures" la facture payée par une structure à une autre (à partir de la ligne 33). Dans la colonne "Structure" (B34), est indiqué le nom de la structure qui reçoit et dans la ligne (34) la structure qui effectue le paiement.
    - le tableau "Mouvements  monétaires entre les structures" fait était des comptes pour chaque structures
### Onglet : suivi des heures
- **uses stories**
    - savoir qui a facturé combien
    - savoir qui a déclaré combien d'heures sociales
- comment ça marche ?
    - c'est de la saisie ligne par ligne
### Onglet : détail du calcul du coût d'une heure
- **uses stories**
    - savoir pourquoi une heure sociale = 20,04€
- comment ça marche ?
    - historiquement, ce coût a été calculé par Scopyleft, lors du précédent marché. En effet, à ce moment là, c'est principalement Scopyleft qui avait embauché des personnes via le dispositif de la Clause Sociale et en général dans le cadre d'un contrat de professionnalisation.
### Onglet : suivi des bons de commande
- **uses stories**
    - savoir quels sont les bons de commandes terminés, en cours et à venir
- comment ça marche ?
    - c'est de la saisies
    - l'état de la commande est déterminé de manière automatique à partir des dates saisies
    - l'estimation du coût de consommation se base sur la durée du bon de commande et fait l'hypothèse que la consommation est linéaire
### Onglet : estimations
- **uses stories**
    - savoir quels sont les potentialités d'embauches
- comment ça marche ?
    - pour que les estimations de mois de salaires envisageables soient calculées, il faut renseigner les bons de commandes et leurs date de début et de fin

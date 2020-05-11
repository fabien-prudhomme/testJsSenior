# Chamboulle tout
### Test JS front Senior

Ce test à pour but de valider des connaissances en en vueJs/js

##### Installation

Forker ce repo
et proposer votre repo en public pour validation

##### Règles 

Le chamboulle tous, repose sur des règles physiques simples, nous partirons des positions suivantes :

        1
      2   3
    4   5   6
    
* Un click sur '5' coche l'ensemble
* Un click sur '4' coche 4, 2 et 1
* Un click sur '6' coche 6, 3 et 1
* Un click sur '2' coche 2 et 1
* Un click sur '3' coche 3 et 1
* Un click sur '1' ne coche que 1

Il faudra compter les points, et les afficher dynamiquement sur la page,
* 4,5 et 6 valent 10 points
* 2 et 3 valent 20 points
* 1 vaut 30 points

L'utilisateur n'aura le droit qu'a 2 tirs, au dela le jeu s'arrete et propose une réinitialisation.

Le comptage des points et le nombres de tir doivent etre persistant et ne doivent pas pouvoir être modifier par un utilisateur avancé...

##### Fonctionnement de vérification

Une pull request, avec vos modification devras être envoyé.
Merci de ne pas minifier votre JS pour qu'il reste humainement lisible.

Vous trouverez dans `ìndex.html` la pyramide déjà prête et un squellette VueJs.

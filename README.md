# hub-spoke

1. Important :

* Point d'entrée central de la connectivité : __réseau virtuel Hub__
Servant aussi de point de connectivité aux *réseaux locaux*.

* Les __réseaux virtuels spoke__ permettent d’isoler les charges de travail dans leurs propres *réseaux virtuels*

*  Deux __réseaux virtuels__ peuvent être connectés à l’aide d’une connexion de __peering__.  
`* Peering connexions non transitives et à faible latence entre des réseaux virtuels.`  
* __Réseau virtuel Azure__ : bloc de construction fondamental pour un réseau privé dans *Azure*.  

* __Pare-feu Azure__ : service de sécurité réseau informatique géré qui protège les *ressources Réseau virtuel Azure*.  
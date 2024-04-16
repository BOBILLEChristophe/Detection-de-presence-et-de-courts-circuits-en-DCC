# Detection-de-presence-et-de-courts-circuits-en-DCC

Voici une petite carte avec à sa base un ATTiny44 qui assure trois fonctions particulièrement intéressantes lorsque l’on cherche à automatiser la gestion de son réseau et en assurer la sécurité. Ces trois fonctions utilisent toutes la lecture de la consommation de courant et agissent de manière appropriée selon les intensités mesurées.

1° - Il est possible de détecter la présence de locomotives et de trains entiers mais aussi de wagons pour peu que ceux-ci aient une capacité résistive.

2° - Une consommation de courant particulièrement élevée peut être fatale au matériel, particulièrement aux décodeurs et aux fils généralement très fins dans les locomotives. Il s’agit dans la majorité des cas d’un court-circuit qu’il faut détecter pour y apporter les réponses appropriées.

3° - La première réponse que l’on puisse apporter en cas de court-circuit est de couper le plus rapidement possible l’alimentation des rails. C’est ce que permet cette carte au travers d’un relais.

Ce dispositif de détections locale s’intègre parfaitement dans le concept des satellites (v1 ou autonomes) mais aussi dans toutes autres configurations en DCC.

Tous les détails sur : https://www.locoduino.org/spip.php?article359

Facile : 

- Ajouter une interface à votre router puis connecter le au serveur.
- Ajouter un autre serveur et faites en un serveur DHCP (la plage d'ip que vous souhaitez)
- Quelle est la différence entre un router et un switch ?
- Faites en sorte que le serveur ajouté soit un serveur WEB et DNS (il vous faudra configurer les machines pour savoir qui interroger pour avoir une réponse DNS)
/!\ Interdiction de mettre le serveur DNS en brute dans la machine /!\
- Ajouter une route par défaut qui pointe vers le serveur.
----------------------------------------------------------------------------------------------------------
Moyen :

- Faites un copier coller du réseau présent. Puis faites en sortes que toutes les machines puissent communiquer entres elles. (Astuce : on parlera ici de route statique)
----------------------------------------------------------------------------------------------------------
Difficile : 
- Pareil, faites un copier coller du réseau présent. Puis ajouter 4 VLANS différents et faites communiquer tous les PC entre eux.
Chaque couleur correspond à un VLAN différent (Adresse réseau au choix).
- Ajouter un serveur DHCP commun aux 4 vlans.
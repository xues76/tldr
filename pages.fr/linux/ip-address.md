# ip address

> Sous commande de gestion IP Address.
> Plus d'informations : <https://www.man7.org/linux/man-pages/man8/ip-address.8.html>.

- Liste les interfaces réseau et leurs adresses IP associées :

`ip address`

- Filtre pour n'afficher que les interfaces réseau actives :

`ip address show up`

- Affiche les informations relatives à une interface réseau spécifique :

`ip address show dev {{eth0}}`

- Ajoute une adresse IP à une interface réseau :

`ip address add {{ip_address}} dev {{eth0}}`

- Supprimer une adresse réseau d'une interface réseau :

`ip address delete {{ip_address}} dev {{eth0}}`

- Supprime l'ensemble des adresses IP sur une portée donnée (scope) depuis une interface réseau :

`ip address flush dev {{eth0}} scope {{global|host|link}}`

# AdvancedPython2BA-Chat
## Auteurs: Hannouni Houda(15056) & Nouhi Fatima(16354) --> Binôme 10

Notre petite application Chat permet de discuter via l'invite de commandes.
Elle comporte une partie en mode Client/Server et une partie en mode peer-to-peer.
<ol> 
<li>Le serveur permet de mémoriser la liste des clients disponibles pour chatter.
  Il retient pour chaque client son pseudo, son adresse IP ainsi que le port de communication.<li>
<li>Le client va se présenter au serveur, ce qui fait quâil sera disponible pour chatter.
  Il peut interroger le serveur pour obtenir la liste des clients disponibles.<li>
<li>Ayant l'adresse IP d'une autre machine, une machine peut lancer un chat avec
  une autre en mode peer-to-peer, tout cela indépendament du server.<li>
<ol>
Lancement du programme:

-Ouvrir l'invite de commande et exécuter le fichier 'ServerClient-.py'
-Ouvrir une autre invite de commande et exécuter le fichier 'ClientClient'
-Se joindre au server en tapant la commande suivante: /join 'adresse IP du Server' 'port du server'
-Entrer son pseudo.

Vous êtes connecté au server et celui-ci a enregistrer votre pseudo !
Taper :
'/send /help' pour connaitre toutes les commandes possibles à exécuter
'/send /clients' pour avoir la liste des clients (pseudo + IP + port)
'/send /quit' pour quitter.

Pour discuter avec un des clients connecté, il suffit de retenir son IP et son port, et de se joindre à celui-ci pour entamer une discussion en mode peer-to-peer !
(taper: /join 'adresse IP du client' 'port du client')

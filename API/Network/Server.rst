Server
======

Cette classe représente le serveur de PyEngine

.. warning:: Cette classe doit être construite via le NetworkManager.

Voici ses méthodes :

stop
----

:Description: Arrête le serveur
:Retourne: Rien
:Paramètres: Rien

.. warning:: Il faut privilégier la fonction stop_server du NetworkManager.

sendto
------

:Description: Envois un message à un client
:Retourne: Rien
:Paramètres:
    - nb <int> : ID du client à qui envoyer le message
    - packet <Packet> : Packet représentant le message

sendall
-------

:Description: Envois un message à tous les clients sauf à l'auteur
:Retourne: Rien
:Paramètres:
    - packet <Packet> : Packet représentant le message

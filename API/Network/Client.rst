Client
======

Cette classe représente le client de PyEngine

.. warning:: Cette classe doit être construite via le NetworkManager.

Voici ses méthodes :

stop
----

:Description: Arrête le client
:Retourne: Rien
:Paramètres: Rien

.. warning:: Il faut privilégier la fonction stop_client du NetworkManager.

send
----

:Description: Envois un message au serveur
:Retourne: Rien
:Paramètre: packet <Packet> : Packet représentant le message

.. note:: Sans modification, le serveur se contentera de renvoyer le packet à tous les autres clients

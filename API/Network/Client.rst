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

:Description: Envois un packet au serveur
:Retourne: Rien
:Paramètres: 
    - type <str> : Type du packet
    - author <int> : Id de l'auteur du packet
    - message <str> : Message du packet

.. note:: Sans modification, le serveur se contentera de renvoyer le packet à tous les autres clients

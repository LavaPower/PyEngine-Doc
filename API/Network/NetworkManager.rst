NetworkManager
==============

Cette classe permet de gérer le network de PyEngine

Constructeur
------------

:Description: Crée l'objet NetworkManager
:Paramètres: Aucun

Voici ses attibuts :

client
------

:Description: Client du jeu
:Type: Client

.. note:: Pour le définir, il faut utiliser la méthode create_client

server
------

:Description: Serveur du jeu
:Type: Server

.. note:: Pour le définir, il faut utiliser la méthode create_server

Voici ses méthodes :

create_client
-------------

:Description: Créer le client du jeu
:Retourne: Rien
:Paramètres:
    - ip <string> : IP du Serveur où se connecter
    - port <string> : Port du Serveur où se connecter
    - callback <function> : Fonction appelé lors de la reception d'un packet

.. note:: La fonction callback doit avoir comme arguments :
    - Le type du packet
    - L'id de l'auteur du packet
    - Le message du packet

create_server
-------------

:Description: Créer le serveur du jeu
:Retourne: Rien
:Paramètres:
    - port <string> : Port du Serveur

stop_client
-----------

:Description: Arrête le client du jeu
:Retourne: Rien
:Paramètres: Rien

stop_server
-----------

:Description: Arrête le serveur du jeu
:Retourne: Rien
:Paramètres: Rien

Loggers
=======

Cette classe permet de symboliser les loggers du jeu

.. warning:: Cette classe ne doit pas être construite. Une variable nommé "loggers" est déjà disponible.

Voici ses méthodes :

create_logger
-------------

:Description: Créer un logger
:Retourne: <Logger> : Logger créé
:Paramètres: 
    - name <string> : Nom du logger à créer
    - file <string> (None) : Chemin du fichier si le 
        logger doit enregistrer les logs
    - stream <bool> (False) : Vrai si le logger doit 
        afficher les logs dans la console

get_logger
----------

:Description: Récupère un logger
:Retourne: <Logger> : Logger
:Paramètre: name <string> : Nom du Logger

.. warning:: Si le logger n'existe pas, il retourne une KeyError

get_all
-------

:Description: Récupère tous les loggers
:Retourne: <Tuple[Logger]> : Tous les loggers
:Paramètres: Rien

to_all
------

:Description: Envoie un message à tous les loggers
:Retourne: Rien
:Paramètres: 
    - action <string> : Urgence du message
    - message <string> : Message à envoyer

.. note:: Les actions sont "debug", "info", "critical", "warning" et "error"


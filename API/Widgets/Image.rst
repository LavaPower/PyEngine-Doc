Image
=====

Cette classe permet de d'afficher une image

Constructeur
------------

:Description: Créer l'objet Image
:Paramètres:
    - position <list> : Position du widget
    - image <string> : Chemin vers l'image
    - size <list> (None) : Taille de l'image

.. note:: Si size vaut None, l'image ne sera pas redimentionnée.

get_image
---------

:Description: Récupère le chemin de l'image
:Retourne: <string> : Chemin de l'image
:Paramètres: Rien

set_image
---------

:Description: Définis l'image
:Retourne: Rien
:Paramètre: <string> : Chemin de l'image

get_size
--------

:Description: Récupère la taille de l'image
:Retourne: <list> : Taille de l'image
:Paramètres: Rien

set_size
--------

:Description: Définis la taille de l'image
:Retourne: Rien
:Paramètre: <list> : Taille de l'image

get_id
------

:Description: Récupère l'id du widget
:Retourne: <int> : Id du widget
:Paramètres: Rien

.. note:: L'id vaut -1 si le widget n'a pas été ajouté à un System.

get_system
----------

:Description: Récupère le system du widget
:Retourne: <UISystem|None> : Système si le widget a été ajouté
:Paramètres: Rien

get_position
------------

:Description: Récupère la position du widget
:Retourne: <list> : Position du widget
:Paramètres: Rien

set_position
------------

:Description: Définis la position du widget
:Retourne: Rien
:Paramètre: <list> : Position du widget

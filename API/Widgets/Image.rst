Image
=====

Cette classe permet d'afficher une image

Constructeur
------------

:Description: Crée l'objet Image
:Paramètres:
    - position <list> : Position du widget
    - image <string> : Chemin vers l'image
    - size <list> (None) : Taille de l'image

.. note:: Si size vaut None, l'image ne sera pas redimensionnée.

get_image
---------

:Description: Récupère le chemin de l'image
:Retourne: <string> : Chemin de l'image
:Paramètre: Rien

set_image
---------

:Description: Définit l'image
:Retourne: Rien
:Paramètre: <string> : Chemin de l'image

get_size
--------

:Description: Récupère la taille de l'image
:Retourne: <list> : Taille de l'image
:Paramètre: Rien

set_size
--------

:Description: Définit la taille de l'image
:Retourne: Rien
:Paramètre: <list> : Taille de l'image

get_id
------

:Description: Récupère l'id du widget
:Retourne: <int> : Id du widget
:Paramètre: Rien

.. note:: L'id vaut -1 si le widget n'a pas été ajouté à un System.

get_system
----------

:Description: Récupère le système du widget
:Retourne:
    <UISystem|None> : Système du widget si il a été ajouté à un UISystem
:Paramètre: Rien

get_position
------------

:Description: Récupère la position du widget
:Retourne: <list> : Position du widget
:Paramètre: Rien

set_position
------------

:Description: Définit la position du widget
:Retourne: Rien
:Paramètre: <list> : Position du widget

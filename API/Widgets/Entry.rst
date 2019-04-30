Entry
=====

Cette classe permet de demander du texte à l'utilisateur

Constructeur
------------

:Description: Créer l'objet Entry
:Paramètres:
    - position <list> : Position du widget
    - width <int> (200) : Largeur du widget

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

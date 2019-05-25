Entry
=====

Cette classe permet de demander du texte à l'utilisateur

Constructeur
------------

:Description: Crée l'objet Entry
:Paramètres:
    - position <list> : Position du widget
    - width <int> (200) : Largeur du widget

get_text
--------

:Description: Récupère le texte du widget
:Retourne: <string> : Texte du widget
:Paramètre: Rien

set_text
--------

:Description: Définit le texte du widget
:Retourne: Rien
:Paramètre: text <string> : Texte du widget

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
:Paramètre: position <list> : Position du widget

is_show
-------

:Description: Savoir si le widget est affiché
:Retourne: <bool> : Vrai si le widget est affiché
:Paramètre: Rien

show
----

:Description: Affiche un widget
:Retourne: Rien
:Paramètre: Rien

hide
----

:Description: Cache un widget
:Retourne: Rien
:Paramètre: Rien

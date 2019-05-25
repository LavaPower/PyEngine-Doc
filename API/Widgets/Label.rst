Label
=====

Cette classe permet d'afficher un texte

Constructeur
------------

:Description: Crée l'objet Label
:Paramètres:
    - position <list> : Position du widget
    - texte <string> : Texte à afficher
    - color <Color> (Color()) : Couleur du texte
    - font <Font> (Font()) : Police du texte

set_color
---------

:Description: Définit la couleur du texte
:Retourne: Rien
:Paramètre: color <Color> : Couleur

get_color
---------

:Description: Récupère la couleur du texte
:Retourne: <Color> : Couleur
:Paramètre: Rien

set_text
--------

:Description: Définit le texte
:Retourne: Rien
:Paramètre: text <string> : Texte

get_text
--------

:Description: Récupère le texte
:Retourne: <string> : Texte
:Paramètre: Rien

set_font
--------

:Description: Définit la police
:Retourne: Rien
:Paramètre: police <Font> : Police

get_font
--------

:Description: Récupère la police
:Retourne: <Font> : Police
:Paramètre: Rien

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

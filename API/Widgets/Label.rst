Label
=====

Cette classe permet de d'afficher un texte

Constructeur
------------

:Description: Crée l'objet Label
:Paramètres:
    - position <list> : Position du widget
    - texte <string> : Texte à afficher
    - color <list> ((255, 255, 255)) : Couleur du texte
    - font <list> (["arial", 15, False, False]) : Police du texte

.. note:: La police est composé comme ceci : [Nom, Taille, Gras, Italique].
    Vous pouvez omettre des éléments mais seulement dans l'ordre.
    
    Exemple : Vous pouvez écrire [Nom, Taille] mais pas [Nom, Gras, Italique]

set_color
---------

:Description: Définit la couleur du texte
:Retourne: Rien
:Paramètre: color <list> : Couleur (RGB ou RGBA)

get_color
---------

:Description: Récupère la couleur du texte
:Retourne: <list> : Couleur (RGB ou RGBA)
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
:Paramètre: police <list> : Police

.. note:: La police est composé comme ceci : [Nom, Taille, Gras, Italique].
    Vous pouvez omettre des éléments mais seulement dans l'ordre.
    
    Exemple : Vous pouvez écrire [Nom, Taille] mais pas [Nom, Gras, Italique]

get_font
--------

:Description: Récupère la police
:Retourne: <list> : Police
:Paramètre: Rien

.. note:: La police est composé comme ceci : [Nom, Taille, Gras, Italique]

get_id
------

:Description: Récupère l'id du widget
:Retourne: <int> : Id du widget
:Paramètre: Rien

.. note:: L'id vaut -1 si le widget n'a pas été ajouté à un System.

get_system
----------

:Description: Récupère le system du widget
:Retourne: <UISystem|None> : Système si le widget a été ajouté
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

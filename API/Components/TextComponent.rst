TextComponent
=============

Cette classe permet de définir un texte à l'entité

.. warning:: Non compatible avec le SpriteComponent

Constructeur
------------

:Description: Crée l'objet TextComponent
:Paramètres:
    - texte <string> : Texte à afficher
    - color <Color> (Color()) : Couleur du texte
    - font <Font> (Font()) : Police du texte

.. warning:: Peut retourner une exception : CompatibilityError

Voici ses méthodes :

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

Label
=====

Cette classe permet d'afficher un texte.

Elle a les mêmes attributs et fonctions que Widget.
Mais elle ajoute aussi les suivants.

Constructeur
------------

:Description: Crée l'objet Label
:Paramètres:
    - position <Vec2> : Position du widget
    - texte <string> : Texte à afficher
    - color <Color> (Color()) : Couleur du texte
    - font <Font> (Font()) : Police du texte
    - background <Color|None> (None) : Couleur de fond

.. note:: Si background est à None la couleur sera transparente.

Voici ses attributs :

background
----------

:Description: Couleur de fond
:Type: None ou Color

color
-----

:Description: Couleur du texte
:Type: Color

font
----

:Description: Police du texte
:Type: Font

text
----

:Description: Texte à afficher
:Type: string

Entry
=====

Cette classe permet de demander du texte à l'utilisateur.

Elle a les mêmes attributs et fonctions que Widget.
Mais elle ajoute aussi les suivants.

Constructeur
------------

:Description: Crée l'objet Entry
:Paramètres:
    - position <Vec2> : Position du widget
    - width <int> (200) : Largeur du widget
    - image <None|string> (None) : Image du widget
    - color <None|Color> (Colors.BLACK.value) : Couleur du texte
    - font <None|Font> (Font()) : Police du texte

.. note:: Si l'image vaut None, le widget utilisera deux rectangles colorés comme image

Voici ses attributs :

text
----

:Description: Text entré dans le widget
:Type: string

sprite
------

:Description: Image de l'Entry
:Type: None ou string

width
-----

:Description: Largeur de l'Entry
:Type: int

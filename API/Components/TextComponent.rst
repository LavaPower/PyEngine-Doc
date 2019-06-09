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
    - background <Color|None> (None) : Couleur de fond
    - scale <int> (1) : Scale du composant

.. note:: Si background est à None la couleur sera transparente.

.. warning:: Peut retourner une exception : CompatibilityError

Voici ses attributs :

scale
-----

:Description: Scale du composant
:Type: int

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

rendered_size
-------------

:Description: Taille du texte rendu
:Type: Tuple[int, int]

entity
------

:Description: Entité lié au composant
:Type: entity

.. note:: L'entité se définit elle même. Elle ne doit pas être modifiée

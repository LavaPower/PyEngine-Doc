SpriteComponent
===============

Cette classe permet de définir un sprite à l'entité

.. warning:: Non compatible avec le TextComponent

Constructeur
------------

:Description: Crée l'objet SpriteComponent
:Paramètres:
    - image <string> : Chemin vers le sprite
    - scale <integer> (1) : "Zoom" sur le sprite
    - rotation <integer> (0) : Rotation du sprite

.. warning:: Peut retourner une exception : CompatibilityError

Voici ses attibuts :

scale
-----

:Description: Scale du composant
:Type: int

size
----

:Description: Taille du sprite
:Type: Tuple[int, int] ou Vec2

.. note:: Size utilise un Vec2 pour se définir mais retourne un Tuple

rotation
--------

:Description: Rotation du sprite
:Type: int

sprite
------

:Description: Chemin vers le sprite
:Type: string

entity
------

:Description: Entité lié au composant
:Type: entity

.. note:: L'entité se définit elle même. Elle ne doit pas être modifiée



EntitySystem
============

Cette classe correspond à la caméra du monde

.. warning:: Si vous utilisez la caméra, faites attention à la position de vos entités.
    PyGame n'incorpore pas de caméra donc pour chaque movement de caméra, PyEngine applique le mouvement inverse aux entités.
    Exemple : Si une entité est en 10, 10 et que l'on met la caméra en 10, 10, l'entité se trouvera en 0, 0.

Voici ses attributs :

position
--------

:Description: Position de la caméra
:Type: Vec2

offset
------

:Description: Offset de la caméra
:Type: Vec2

zoom
----

:Description: Zoom de la caméra
:Type: int

entity_follow
-------------

:Description: Entité suivie par la caméra
:Type: Entity ou None

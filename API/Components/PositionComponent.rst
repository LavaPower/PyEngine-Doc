PositionComponent
=================

Cette classe permet de définir une position à l'entité

Constructeur
------------

:Description: Crée l'objet PositionComponent
:Paramètres:
    - position <Vec2> : Position de l'entité
    - offset <Vec2> (Vec2()) : Offset de l'entité

.. note:: L'offset n'est utile que dans le cas d'entité 
    attachée à une autre entité.

Voici ses attributs :

position
--------

:Description: Position de l'entité
:Type: Vec2

entity
------

:Description: Entité lié au composant
:Type: entity

.. note:: L'entité se définit elle même. Elle ne doit pas être modifiée


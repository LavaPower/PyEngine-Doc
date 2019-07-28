PhysicsComponent
================

Cette classe permet de définir une physique à l'entité

Constructeur
------------

:Description: Crée l'objet PhysicsComponent
:Paramètres:
    - affectbygravity <bool> (True) : Affecté par la gravité ou non
    - gravity_force <int> (5) : Puissance de la gravité
    - callback <function> (None) : Fonction appelé lors de la collision

Voici ses attributs :

gravity
-------

:Description: Force de la gravité appliqué
:Type: int

callback
--------

:Description: Fonction a appelé lors d'une collision
:Type: Function

.. note:: La fonction doit avec deux arguments : l'objet avec lequel il a eu collision et les informations de la collision

.. note:: Les informations de la cause sont représentées par une classe ayant comme attributs :
    - La cause de la collision (cause)
    - Le coté de la collision (cote)

entity
------

:Description: Entité lié au composant
:Type: entity

.. note:: L'entité se définit elle même. Elle ne doit pas être modifiée

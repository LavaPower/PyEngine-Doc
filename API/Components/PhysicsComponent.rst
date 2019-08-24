PhysicsComponent
================

Cette classe permet de définir une physique à l'entité

Constructeur
------------

:Description: Crée l'objet PhysicsComponent
:Paramètres:
    - affectbygravity <bool> (True) : Affecté par la gravité ou non
    - friction <float> (.5) : Friction de l'objet
    - elasticity <float> (.5) : Elasticité de l'objet
    - mass <int> (1) : Masse de l'objet
    - solid <bool> (True) : Si vrai, l'objet ne pourra pas être traversé
    - can_rot <bool> (True) : Si vrai, la rotation ne sera pas bloquée
    - callback <function> (None) : Fonction appelé lors de la collision

Voici ses attributs :

affectbygravity
---------------

:Description: Affecté par la gravité ou non
:Type: bool

friction
--------

:Description: Friction de l'objet
:Type: float

elasticity
----------

:Description: Elasticité de l'objet
:Type: float

mass
----

:Description: Masse de l'objet
:Type: int

solid
-----

:Description: Si vrai, l'objet ne pourra pas être traversé
:Type: bool

can_rot
-------

:Description: Si vrai, la rotation ne sera pas bloquée
:Type: bool

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

Vec2
====

Cette classe permet de symboliser un vecteur de dimention 2

Constructeur
------------

:Description: Crée l'objet Vec2
:Paramètres:
    - x <int> (0) : Coordonnée X
    - y <int> (0) : Coordonnée Y

Voici ses attributs :

coords
------

:Description: Coordonnées du vecteur
:Type: Tuple[int, int]

length
------

:Description: Longueur du vecteur
:Type: int

.. note:: Length n'a pas de setter, vous ne pouvez pas la définir.
    Cependant, elle est modifié par les coordonnées.

Voici ses méthodes :

normalized
----------

:Description: Retourne le vecteur normalisé
:Retourne: <Vec2>
:Paramètres: Rien


__add__
-------

:Description: Correspond à l'addition
:Retourne: <Vec2>
:Paramètre: <Vec2|int>

__sub__
-------

:Description: Correspond à la soustraction
:Retourne: <Vec2>
:Paramètre: <Vec2|int>

__mul__
-------

:Description: Correspond à la multiplication
:Retourne: <Vec2>
:Paramètre: <Vec2|int>

__truediv__
-----------

:Description: Correspond à la division
:Retourne: <Vec2>
:Paramètre: <Vec2|int>

__iter__
--------

:Description: Correspond à l'interateur (for i in Vec2)
:Retourne: <int>
:Paramètre: Rien 

__repr__
--------

:Description: Correspond à la représentation en string
:Retourne: <string>
:Paramètre: Rien

__eq__
------

:Description: Correspond à la comparaison '=='
:Retourne: <bool>
:Paramètre: <Vec2>

__neg__
-------

:Description: Correspond à la négation
:Retourne: <Vec2>
:Paramètre: Rien

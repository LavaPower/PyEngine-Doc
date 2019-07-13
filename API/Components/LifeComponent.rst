LifeComponent
=============

Cette classe permet de définir une vie à l'entité.

Constructeur
------------

:Description: Crée l'objet LifeComponent
:Paramètres: 
    - maxlife <int> (100) : Vie maximum
    - callback <function> (None) : Fonction s'activant quand la vie arrive à 0 

Voici ses attributs :

life
----

:Description: Vie actuelle
:Type: int

.. note:: life est compris entre 0 et maxlife.
    Si la valeur est inférieur à 0 alors life = 0.
    Si la valeur est supérieur à maxlife alors life = maxlife.

maxlife
-------

:Description: Vie maximum
:Type: int

callback
--------

:Description: Fonction s'activant quand la vie arrive à 0 
:Type: function

entity
------

:Description: Entité lié au composant
:Type: entity

.. note:: L'entité se définit elle même. Elle ne doit pas être modifiée

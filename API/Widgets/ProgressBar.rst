ProgressBar
===========

Cette classe permet de d'afficher une barre de progression.

Elle a les mêmes attributs et fonctions que Widget.
Mais elle ajoute aussi les suivants.

Constructeur
------------

:Description: Crée l'objet ProgressBar
:Paramètres:
    - position <Vec2> : Position du widget
    - size <Vec2> (Vec2(150, 10)) : Taille du widget
    - sprites <Tuple[str, str]> (None) : Sprites du widget

.. note:: Sprites est constitué de deux strings : le premier pour l'image de fond, le second pour celle de devant

.. note:: Si sprites est égal à None, le widget sera constitué de rectangle blanc, noir et verre pour la barre

Voici ses attributs :

value
-----

:Description: Valeur en pourcent de la barre
:Type: int 

.. note:: Si vous donnez une valeur non comprise entre 0 et 100, la valeur sera automatiquement remise dans l'intervale

size
----

:Description: Taille du widget
:Type: Vec2

sprites
-------

:Description: Sprites du Widget
:Type: Tuple[str, str] ou None

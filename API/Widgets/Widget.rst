Widget
======

Cette classe sert de base à tous les autres widgets. 
Elle ne doit pas être utilisée en l'état.

.. note:: Le constructeur n'est pas listé vu qu'il ne doit pas être utilisé directement.

Voici ses attributs :

identity
--------

:Description: Id du widget
:Type: int

.. note:: Le système définit l'id lui même. Elle ne doit pas être changée.

system
------

:Description: Système gérant le widget
:Type: UISystem

.. note:: Le système se définit lui même. Il ne doit pas être changé.

position
--------

:Description: Position du widget
:Type: Vec2

Voici ses méthodes :

is_show
-------

:Description: Permet de savoir si le widget est affiché
:Retourne: <boolean> : Vrai si le widget est affiché, sinon faux
:Paramètre: Rien

show
----

:Description: Affiche un widget
:Retourne: Rien
:Paramètre: Rien

hide
----

:Description: Cache un widget
:Retourne: Rien
:Paramètre: Rien

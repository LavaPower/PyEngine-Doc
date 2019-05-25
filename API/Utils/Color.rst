Color
=====

Cette classe permet de symboliser une couleur

Constructeur
------------

:Description: Crée l'objet Color
:Paramètres:
    - r <int> (255) : Rouge
    - g <int> (255) : Vert
    - b <int> (255) : Bleu

set
---

:Description: Définit la couleur via une autre couleur
:Retourne: Rien
:Paramètre: color <Color> : Couleur

clone
-----

:Description: Clone la couleur
:Retourne: <Color> : Nouvelle couleur
:Paramètre: Rien

.. note:: Cette méthode est utile pour les couleurs définies dans l'énumération Colors.
    Sans cette méthode, vous ne pouvez pas modifier les couleurs de l'énumération.

lighter
-------

:Description: Eclaircit la couleur
:Retourne: <color> : Nouvelle Couleur
:Paramètre: Rien

darker
------

:Description: Assombrit la couleur
:Retourne: <color> : Nouvelle Couleur
:Paramètre: Rien

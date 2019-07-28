AnimatedImage
=============

Cette classe permet d'afficher une image avec une animation.

Elle a les mêmes attributs et fonctions que Widget.
Mais elle ajoute aussi les suivants.

Constructeur
------------

:Description: Crée l'objet AnimatedImage
:Paramètres:
    - position <Vec2> : Position du widget
    - sprites <List[str]> : Chemin vers les images
    - timer <int> : Timer pour l'animation
    - size <None|Tuple[int, int]> (None) : Taille de l'image

.. note:: Si size vaut None, l'image ne sera pas redimensionnée.

Voici ses attributs :

size
----

:Description: Taille de l'image
:Type: Tuple[int, int]

timer
-----

:Description: Timer pour l'animation
:Type: int

sprite
------

:Description: Chemin vers l'image actuelle
:Type: str

sprites
-------

:Description: Chemin vers les images
:Type: List[str]

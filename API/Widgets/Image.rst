Image
=====

Cette classe permet d'afficher une image.

Elle a les mêmes attributs et fonctions que Widget.
Mais elle ajoute aussi les suivants.

Constructeur
------------

:Description: Crée l'objet Image
:Paramètres:
    - position <Vec2> : Position du widget
    - sprite <string> : Chemin vers l'image
    - size <None|Tuple[int, int]> (None) : Taille de l'image

.. note:: Si size vaut None, l'image ne sera pas redimensionnée.

Voici ses attributs :

size
----

:Description: Taille de l'image
:Type: Tuple[int, int]

sprite
------

:Description: Chemin vers l'image
:Type: string

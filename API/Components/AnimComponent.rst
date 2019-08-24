AnimComponent
=============

Cette classe permet de d'animer le sprite de l'entité

Constructeur
------------

:Description: Crée l'objet AnimComponent
:Paramètres:
    - timer <int> : Temps en frames pour changer de sprites
    - images <Tuple[string]> : Liste des chemins des sprites
    - flipx <bool> (False) : Si vrai, les images vont être retournées suivant l'axe X
    - flipy <bool> (False) : Si vrai, les images vont être retournées suivant l'axe Y

.. note:: Il est nécessaire d'avoir un SpriteComponent pour ajouter un AnimComponent
    
Voici ses attributs :

time
----

:Description: Temps en frames pour changer de sprites
:Type: int

images
------

:Description: Liste des chemins des sprites
:Type: Tuple[string]

flipx
-----

:Description: Si vrai, les images vont être retourner suivant l'axe X
:Type: bool

flipy
-----

:Description: Si vrai, les images vont être retourner suivant l'axe y
:Type: bool

entity
------

:Description: Entité lié au composant
:Type: entity

.. note:: L'entité se définit elle même. Elle ne doit pas être modifiée


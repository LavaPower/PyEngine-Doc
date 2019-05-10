SpriteComponent
=================

Cette classe permet de définir un sprite à l'entité

.. warning:: Non compatible avec le TextComponent

Constructeur
------------

:Description: Crée l'objet SpriteComponent
:Paramètres:
    - image <string> : Chemin vers le sprite
    - scale <integer> (1) : "Zoom" sur le sprite
    - rotation <integer> (0) : Rotation du sprite

.. warning:: Peut retourner une exception : CompatibilityError

Voici ses méthodes :

set_scale
---------

:Description: Change le "zoom" du sprite
:Retourne: Rien
:Paramètre: scale <integer> : "Zoom" du sprite

set_size
--------

:Description: Change la taille du sprite
:Retourne: Rien
:Paramètre: size <list> : taille du sprite

.. note:: Réinitialise la scale du sprite

set_rotation
------------

:Description: Change la rotation du sprite
:Retourne: Rien
:Paramètre: rotation <integer> : Rotation du sprite

set_sprite
----------

:Description: Change le sprite
:Retourne: Rien
:Paramètre: sprite <string> : Chemin vers le sprite

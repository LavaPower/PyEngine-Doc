Tilemap
=======

Cette classe permet de créer une tilemap à partir de fichier de Tiled (exporté en .json)

.. note:: Cette classe hérite de "Entity". De ce fait, toutes ses méthodes et attributs fonctionne ici.

Constructeur
------------

:Description: Crée l'objet Tilemap
:Paramètres:
    - pos <Vec2> : Position de la tilemap
    - file <string> : Chemin du fichier .json
    - scale <integer> (1) : Scale de la tilemap

Voici ses attributs :

scale
-----

:Description: Scale de la tilemap
:Type: integer

Tilemap
=======

Cette classe correspond à une tilemap de votre jeu.

.. note:: Cette classe utilise le fichier .json donné par Tiled

.. note:: Par défaut, les tiles ont une physique sans affectation gravitationnelle

Constructeur
------------

:Description: Crée l'objet Tilemap
:Paramètres:
    - position <Vec2> : Position de la tilemap
    - file <str> : Chemin vers le fichier .json
    - Scale <int> (1) : Scale de la tilemap

Voici ses attributs :

identity
--------

:Description: Id de l'entité
:Type: int

.. note:: Le système définit l'id lui même. Elle ne doit pas être changée.

scale
-----

:Description: Scale de la tilemap
:Type: int

tiles
-----

:Description: Liste des tiles formant la tilemap
:Type: List[Entity]

system
------

:Description: Système gérant l'entité
:Type: EntitySystem

.. note:: Le système se définit lui même. Il ne doit pas être changé.

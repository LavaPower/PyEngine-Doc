LifeBarComponent
================

Cette classe permet de définir une vie à l'entité et, optionnellement, une barre de vie.

Constructeur
------------

:Description: Créer l'objet LifeBarComponent
:Paramètres:
    - maxlife <int> (100) : Vie maximum
    - sprites <list> (None) : Sprites de la barre de vie
    - offset <list> (None) : Offset de la barre de vie

Voici ces méthodes :

create_life_sprites
-------------------

:Description: Créer les entités de la barre de vie
:Retourne: Rien
:Paramètres: Rien

.. warning:: Utilisable seulement si sprites a été défini dans le Constructeur

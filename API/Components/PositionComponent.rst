PositionComponent
=================

Cette classe permet de définir une position à l'entité

Constructeur
------------

:Description: Créer l'objet PositionComponent
:Retourne: Rien
:Paramètres:
    - position <list> : Position de l'entité
    - offset <list> ([0, 0]) : Offset de l'entité

.. note:: L'offset n'est utile que dans le cas d'entité 
    attaché à une autre entité.

Voici ses méthodes :

get_position
------------

:Description: Récupère la position
:Retourne: <list> : Position de l'entité
:Paramètres: Rien

set_position
------------

:Description: Définis la position
:Retourne: Rien
:Paramètre: position <list> : Position de l'entité

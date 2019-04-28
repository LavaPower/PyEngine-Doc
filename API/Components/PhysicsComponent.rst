PhysicsComponent
================

Cette classe permet de définir une physique à l'entité

Constructeur
------------

:Description: Créer l'objet PhysicsComponent
:Paramètres:
    - affectbygravity <bool> (True) : Affecté par la gravité ou non
    - gravity_force <int> (5) : Puissance de la gravité

Voici ces méthodes :

set_callback
------------

:Description: Définis le callback de la collision
:Retourne: Rien
:Paramètres:
    - function <Function> : Fonction lancé au moment du callback

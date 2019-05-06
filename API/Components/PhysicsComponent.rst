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

get_gravity
-----------

:Description: Récupère la force de gravité
:Retourne: <int> : Force de gravité
:Paramètres: Rien

set_gravity
-----------

:Description: Définis la force de gravité
:Retourne: Rien
:Paramètre: gravity <int> : Force de gravité

set_callback
------------

:Description: Définis le callback de la collision
:Retourne: Rien
:Paramètres:
    - function <Function> : Fonction lancé au moment du callback

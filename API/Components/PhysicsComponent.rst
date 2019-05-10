PhysicsComponent
================

Cette classe permet de définir une physique à l'entité

Constructeur
------------

:Description: Crée l'objet PhysicsComponent
:Paramètres:
    - affectbygravity <bool> (True) : Affecté par la gravité ou non
    - gravity_force <int> (5) : Puissance de la gravité

Voici ces méthodes :

get_gravity
-----------

:Description: Récupère la force de gravité
:Retourne: <int> : Force de gravité
:Paramètre: Rien

set_gravity
-----------

:Description: Définit la force de gravité
:Retourne: Rien
:Paramètre: gravity <int> : Force de gravité

set_callback
------------

:Description: Définit le callback de la collision
:Retourne: Rien
:Paramètres:
    - function <Function> : Fonction lancée au moment du callback

.. note:: Un callback est simplement une fonction lancée
    suivant des évènements précis (Ici une collision).

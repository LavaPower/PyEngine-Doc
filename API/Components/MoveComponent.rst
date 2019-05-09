MoveComponent
=============

Cette classe permet de faire bouger automatiquement une entité

Constructeur
------------

:Description: Crée l'objet MoveComponent
:Paramètres:
    - direction <list> : Direction du mouvement
    - speed <int> (5) : Vitesse du mouvement

.. note:: direction est un liste où le premier nombre correspond au mouvement en x et le second en y.
    Cet liste ne doit contenir que des 1, -1 et 0. Exemple : (0, 1) créra un mouvement vers le bas

Voici ses méthodes :

get_speed
---------

:Description: Récupère la vitesse
:Retourne: <int> : Vitesse du mouvement
:Paramètre: Rien

set_speed
---------

:Description: Définit la vitesse
:Retourne: Rien
:Paramètre: speed <int> : Vitesse du mouvement

get_direction
-------------

:Description: Récupère la direction
:Retourne: <list> : Direction du mouvement
:Paramètre: Rien

set_direction
-------------

:Description: Définit la direction
:Retourne: Rien
:Paramètre: direction <list> : Direction du mouvement

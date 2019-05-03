Enumérations
============

PyEngine incorpore beaucoup d'énumérations utilisées dans ses différentes classes. En voici la liste :

ControlType
-----------

:Description: Correspond aux différents types de controles de la 
    classe ControlComponent
:Valeurs:
    - FOURDIRECTION : L'objet se déplace dans les quatres directions.
    - CLASSICJUMP : L'objet peut se déplacer à gauche et à 
        droite et faire un saut simple
    - DOUBLEJUMP : Comme le CLASSICJUMP mais avec un double saut
    - CLICKFOLLOW : L'ojet se déplace vers l'endroit du clique de la souris

MouseButton
-----------

:Description: Correspond aux différents boutons de la souris
:Valeurs:
    - LEFTCLICK : Clique gauche
    - MIDDLECLICK : Clique molette
    - RIGHTCLICK : Clique droit

CollisionCauses
---------------

:Description: Correspond aux différentes causes d'une collision
:Valeurs:
    - UNKNOWN : Cause inconnu
    - GRAVITY : Causée par la gravité
    - LEFTCONTROL : Causée par un déplacement à gauche 
        créé par un ControlComponent
    - RIGHTCONTROL : Causée par un déplacement à droite 
        créé par un ControlComponent
    - UPCONTROL : Causée par un déplacement en haut 
        créé par un ControlComponent
    - DOWNCONTROL : Causée par un déplacement en bas 
        créé par un ControlComponent
    - MOVECOMPONENT : Causée par un déplacement crée par
        un MoveComponent

.. note:: Si une collision à lieu à cause d'un saut, c'est la cause GRAVITY qui sera affichée.

WorldCallbacks
--------------

:Description: Correspond aux différents types de callback renvoyé par le monde
:Valeurs:
    - FALL : Activé quand un élément dépasse le bas de l'écran

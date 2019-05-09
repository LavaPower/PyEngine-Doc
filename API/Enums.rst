Enumérations
============

PyEngine incorpore beaucoup d'énumérations utilisées dans ses différentes classes. En voici la liste :

ControlType
-----------

:Description: Correspond aux différents types de contrôles de la 
    classe ControlComponent
:Valeurs:
    - FOURDIRECTION : L'objet se déplace dans les quatres directions.
    - CLASSICJUMP : L'objet se déplace latéralement et fait un saut simple
    - DOUBLEJUMP : Comme le CLASSICJUMP mais avec un double saut
    - CLICKFOLLOW : L'objet se déplace vers l'endroit du clic de la souris
    - LEFTRIGHT : L'objet se déplace latéralement, sans saut
    - UPDOWN : L'objet se déplace de bas en haut

Controls
--------

:Description: Correspond aux contrôles utilisables dans PyEngine
:Valeurs:
    - UPJUMP : Direction vers le haut (sert aussi au saut)
    - LEFT : Direction vers la gauche
    - RIGHT : Direction vers la droite
    - DOWN : Direction vers le bas

MouseButton
-----------

:Description: Correspond aux différents boutons de la souris
:Valeurs:
    - LEFTCLICK : Clic gauche
    - MIDDLECLICK : Clic molette
    - RIGHTCLICK : Clic droit

CollisionCauses
---------------

:Description: Correspond aux différentes causes d'une collision
:Valeurs:
    - UNKNOWN : Cause inconnu
    - GRAVITY : Causée par la gravité
    - LEFTCONTROL : Causée par un déplacement à gauche du ControlComponent
    - RIGHTCONTROL : Causée par un déplacement à droite du ControlComponent
    - UPCONTROL : Causée par un déplacement en haut du ControlComponent
    - DOWNCONTROL : Causée par un déplacement en bas du ControlComponent
    - MOVECOMPONENT : Causée par un déplacement du MoveComponent

.. note:: Si une collision à lieu à cause d'un saut, c'est la cause GRAVITY qui sera affichée.

WorldCallbacks
--------------

:Description: Correspond aux différents types de callback renvoyé par le monde
:Valeurs:
    - OUTOFWINDOW : Activé quand un élément dépasse les bords de l'écran

.. note:: Un callback est simplement une fonction lancée
    suivant des évènements précis.

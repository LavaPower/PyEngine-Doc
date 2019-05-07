ControlComponent
================

Cette classe permet de controler l'entité

Constructeur
------------

:Description: Créer l'objet ControlComponent
:Paramètres:
    - controltype <ControlType> : Type de controle
    - speed <integer> (5) : Vitesse du mouvement
    
Voici ses méthodes :

get_control
-----------

:Description: Récupère un controle
:Retourne: <int> : Constante correspondant à la touche
:Paramètre: <Controls> : Controle à récupérer

set_control
-----------

:Description: Définis un controle
:Retourne: Rien
:Paramètres: 
    - name <Controls> : Controle à récupérer
    - key <int> : Constante correspondant à la touche

get_speed
---------

:Description: Récupère la vitesse
:Retourne: <int> : Vitesse du mouvement
:Paramètres: Rien

set_speed
---------

:Description: Définis la vitesse
:Retourne: Rien
:Paramètre: speed <int> : Vitesse du mouvement

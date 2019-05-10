ControlComponent
================

Cette classe permet de contrôler l'entité

Constructeur
------------

:Description: Crée l'objet ControlComponent
:Paramètres:
    - controltype <ControlType> : Type de contrôle
    - speed <integer> (5) : Vitesse du mouvement
    
Voici ses méthodes :

get_control
-----------

:Description: Récupère un contrôle
:Retourne: <int> : Constante correspondant à la touche
:Paramètre: <Controls> : Contrôle à récupérer

set_control
-----------

:Description: Définit un contrôle
:Retourne: Rien
:Paramètre: 
    - name <Controls> : Contrôle à récupérer
    - key <int> : Constante correspondant à la touche

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

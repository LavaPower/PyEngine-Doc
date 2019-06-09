ControlComponent
================

Cette classe permet de contrôler l'entité

Constructeur
------------

:Description: Crée l'objet ControlComponent
:Paramètres:
    - controltype <ControlType> : Type de contrôle
    - speed <int> (5) : Vitesse du mouvement
    
Voici ses attributs :

speed
-----

:Description: Vitesse du mouvement
:Type: int

entity
------

:Description: Entité lié au composant
:Type: entity

.. note:: L'entité se définit elle même. Elle ne doit pas être modifiée

Voici ses méthodes :

set_control
-----------

:Description: Définit un controle
:Retourne: Rien
:Paramètres:
    - control <Controls> : Controle à définir
    - key <const> : Touche correspondant au controle

get_control
-----------

:Description: Récupère un controle
:Retourne: <const> : Touche correspondant au controle
:Paramètre: control <Controls> : Controle à récupérer 

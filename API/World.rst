World
=====

Cette classe correspond à un monde de votre jeu

Constructeur
------------

:Description: Crée l'objet Monde
:Paramètres:
    - window <Window> : Fenêtre liée au monde
    - gravity <Tuple[int, int]> ([0, -900]) : Gravité du monde

Voici ses attributs :

window
------

:Description: Fenêtre liée au monde
:Type: Window

gravity
-------

:Description: Gravité du monde
:Type: Tuple[int, int]

Voici ses méthodes :

get_system
----------

:Description: Récupère un système du monde
:Retourne: <Systems|None> : Système du type <classe> s'il existe
:Paramètre: <Systems> : Classe du système à récupérer

.. note:: Systems fait référence aux systèmes (EntitySystem, UISystem, SoundSystem, CameraSystem et MusicSystem)

World
=====

Cette classe correspond à un monde de votre jeu

Constructeur
------------

:Description: Crée l'objet Monde
:Paramètre: window <Window> : Fenêtre liée au monde

Voici ses attributs :

window
------

:Description: Fenêtre liée au monde
:Type: Window

Voici ses méthodes :

get_system
----------

:Description: Récupère un système du monde
:Retourne: <Systems|None> : Système du type <classe> s'il existe
:Paramètre: <Systems> : Classe du système à récupérer

.. note:: Systems fait référence aux systèmes (EntitySystem, UISystem, SoundSystem, CameraSystem et MusicSystem)

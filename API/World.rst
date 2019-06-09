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

set_callback
------------

:Description: Définit un Callback
:Retourne: Rien
:Paramètres:
    - callback <WorldCallbacks> : Callback à définir
    - function <Function> : Fonction lancée au moment du callback

Les callsbacks peuvent demander des paramètres.
Il faut donc les fournir dans la fonction lancée.

:OUTOFWINDOW:
    - <Entity> - Entité qui dépasse les bords
    - <Vec2> - position de l'entité

.. note:: Un callback est simplement une fonction lancée
    suivant des évènements précis.

.. warning:: Peut retourner une exception : TypeError

get_system
----------

:Description: Récupère un système du monde
:Retourne: <Systems|None> : Système du type <classe> s'il existe
:Paramètre: <Systems> : Classe du système à récupérer

.. note:: Systems fait référence aux systèmes (EntitySystem, UISystem, SoundSystem, CameraSystem et MusicSystem)

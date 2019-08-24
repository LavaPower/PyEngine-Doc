Window
======

Cette classe correspond à la fenêtre ouverte par votre jeu.

Constructeur
------------

:Description: Crée l'objet Window
:Paramètres:
    - width <integer> : Largeur de la fenêtre
    - height <integer> : Hauteur de la fenêtre
    - color <Color> (Color()) : Couleur de fond
    - title <string> ("PyEngine") : Titre de la fenêtre
    - icon <string> (None) : Chemin vers l'icon de la fenêtre
    - limit_fps <int> (None) : Nombre de FPS maximum
    - update_rate <int> (60) : Nombre d'update par seconde
    - debug <boolean> (False) : Mode debug

.. note:: Si l'icon vaut "None" la fenêtre aura l'icon de PyGame

.. note:: Si limit_fps vaut "None" les FPS ne seront pas bloqués

Voici ses attributs :

title
-----

:Description: Titre de la fenêtre
:Type: string

color
-----

:Description: Couleur de fond de la fenêtre
:Type: Color

update_rate
-----------

:Description: Nombre d'update par seconde
:Type: int

limit_fps
---------

:Description: Nombre de FPS maximum
:Type: int

size
----

:Description: Taille de la fenêtre
:Type: Tuple[int, int]

debug
-----

:Description: Mode débug
:Type: boolean

world
-----

:Description: Monde de la fenêtre
:Type: World

Voici ses méthodes :

stop
----

:Description: Arrête le jeu
:Retourne: Rien
:Paramètre: Rien

run
---

:Description: Lance le jeu
:Retourne: Rien
:Paramètre: Rien


set_callback
------------

:Description: Définit un Callback
:Retourne: Rien
:Paramètres:
    - callback <WindowCallbacks> : Callback à définir
    - function <Function> : Fonction lancée au moment du callback

Les callbacks peuvent demander des paramètres.
Il faut donc les fournir dans la fonction lancée.

:OUTOFWINDOW:
    - <Entity> - Entité qui dépasse les bords
    - <Vec2> - Position de l'entité
:STOPWINDOW: Rien
:CHANGEWORLD:
    - <World> - Ancien Monde
    - <World> - Nouveau Monde

.. note:: Un callback est simplement une fonction lancée
    suivant des évènements précis.

.. warning:: Peut retourner une exception : TypeError

.. warning:: Peut retourner les exceptions : NoObjectError

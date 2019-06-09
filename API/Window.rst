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
    - debug <boolean> (False) : Mode debug

.. note:: Si l'icon vaut "None" la fenêtre aura l'icon de PyGame

Voici ses attributs :

title
-----

:Description: Titre de la fenêtre
:Type: string

color
-----

:Description: Couleur de fond de la fenêtre
:Type: Color

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

.. warning:: Peut retourner les exceptions : NoObjectError

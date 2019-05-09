Window
======

Cette classe correspond à la fenêtre ouverte par votre jeu.

Constructeur
------------

:Description: Crée l'objet Window
:Paramètres:
    - width <integer> : Largeur de la fenêtre
    - height <integer> : Hauteur de la fenêtre
    - color <list> (None) : Couleur de fond
    - debug <boolean> (False) : Mode debug

.. note:: Si color est égal à None, color vaut (0, 0, 0) (soit noir)

Voici ces méthodes :

set_color
---------

:Description: Change la couleur de la fenêtre
:Retourne: Rien
:Paramètre: color <list> : Couleur de la fenêtre

get_color
---------

:Description: Récupère la couleur de la fenêtre
:Retourne: <list> : Couleur de la fenêtre
:Paramètre: Rien

set_debug
---------

:Description: Change si la fenêtre est en mode debug
:Retourne: Rien
:Paramètre: debug <boolean> : Mode debug de la fenêtre

get_debug
---------

:Description: Vérifie que la fenêtre est en mode debug
:Retourne: <boolean> : Mode debug de la fenêtre
:Paramètre: Rien

set_title
---------

:Description: Change le titre de la fenêtre
:Retourne: Rien
:Paramètre: title <string> : Nouveau titre de la fenêtre

get_title
---------

:Description: Récupère le titre de la fenêtre
:Retourne: <string> : Titre de la fenêtre
:Paramètre: Rien

add_state
---------

:Description: Ajoute un GameState à la fenêtre
:Retourne: Rien
:Paramètre: state <GameState> : GameState à ajouter

set_current_state
-----------------

:Description: Définit la GameState actuelle
:Retourne: Rien
:Paramètre: name <string> : Nom de la GameState à définir comme actuelle

get_current_state
-----------------

:Description: Récupère la GameState actuelle
:Retourne: <GameState> : GameState actuelle
:Paramètre: Rien

get_state
---------

:Description: Récupère une GameState à partir de son nom
:Retourne: <GameState|None> : GameState dont le nom est <name> 
    ou Rien si elle n'existe pas.
:Paramètre: name <string> : Nom de la GameState à récupérer

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

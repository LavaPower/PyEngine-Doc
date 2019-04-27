Window
======

Cette classe correspond à la fenêtre ouverte par votre jeu.

Construteur
-----------

:Description: Créer l'objet Window
:Retourne: Rien
:Paramètres:
    - width <integer> : Largeur de la fenêtre
    - height <integer> : Hauteur de la fenêtre
    - debug <boolean> (False) : Mode debug (par défaut : Faux)

Voici ces méthodes :

set_title
---------

:Description: Permet de changer le titre de la fenêtre
:Retourne: Rien
:Paramètres: 
    - title <string> : Nouveau titre de la fenêtre

get_title
---------

:Description: Permet de récupérer le titre de la fenêtre
:Retourne: <string> : Titre de la fenêtre
:Paramètres: Rien

add_state
---------

:Description: Permet d'ajouter un GameState à la fenêtre
:Retourne: Rien
:Paramètres:
    - state <GameState> : GameState à ajouter

set_current_state
-----------------

:Description: Permet de définir la GameState actuelle
:Retourne: Rien
:Paramètres:
    - name <string> : Nom de la GameState à définir comme actuelle

get_current_state
-----------------

:Description: Permet de récupérer la GameState actuelle
:Retourne: <GameState> : GameState actuelle
:Paramètres: Rien

get_state
---------

:Description: Permet de récupérer une GameState à partir de son nom
:Retourne: <GameState|None> : GameState dont le nom est <name> 
    ou Rien si elle n'existe pas.
:Paramètres:
    - name <string> : Nom de la GameState à récupérer

stop
----

:Description: Permet d'arrêter le jeu
:Retourne: Rien
:Paramètres: Rien

run
---

:Description: Permet de lancer le jeu
:Retourne: Rien
:Paramètres: Rien

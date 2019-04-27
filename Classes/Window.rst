Window
======

Cette classe correspond à la fenêtre ouverte par votre jeu.

set_title
---------

:Description: Permet de changer le titre de la fenêtre
:Paramètres: 
    - title <string> : Nouveau titre de la fenêtre
:Retourne: Rien

get_title
---------

:Description: Permet de récupérer le titre de la fenêtre
:Paramètres: Rien
:Retourne: <string> : Titre de la fenêtre

add_state
---------

:Description: Permet d'ajouter un GameState à la fenêtre
:Paramètres:
    - state <GameState> : GameState à ajouter
:Retourne: Rien

set_current_state
-----------------

:Description: Permet de définir la GameState actuelle
:Paramètres:
    - name <string> : Nom de la GameState à définir comme actuelle
:Retourne: Rien

get_current_state
-----------------

:Description: Permet de récupérer la GameState actuelle
:Paramètres: Rien
:Retourne: <GameState> : GameState actuelle

get_state
---------

:Description: Permet de récupérer une GameState à partir de son nom
:Paramètres:
    - name <string> : Nom de la GameState à récupérer
:Retourne: <GameState|None> : GameState dont le nom est <name> ou Rien si elle n'existe pas.

stop
----

:Description: Permet d'arrêter le jeu
:Paramètres: Rien
:Retourne: Rien

run
---

:Description: Permet de lancer le jeu
:Paramètres: Rien
:Retourne: Rien

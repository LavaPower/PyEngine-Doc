GameState
=========

Cette classe correspond à un état précis de votre jeu

Constructeur
------------

:Description: Crée l'objet GameState
:Paramètre: name <string> : Nom de la GameState

Voici ces méthodes :

set_callback
------------

:Description: Définit un Callback
:Retourne: Rien
:Paramètres:
    - callback <StateCallbacks> : Callback à définir
    - function <Function> : Fonction lancée au moment du callback

Les callsbacks peuvent demander des paramètres.
Il faut donc les fournir dans la fonction lancée.

:OUTOFWINDOW:
    - <Entity> - Entité qui dépasse les bords
    - <List> - position de l'entité

.. note:: Un callback est simplement une fonction lancée
    suivant des évènements précis.

.. warning:: Peut retourner une exception : TypeError

get_system
----------

:Description: Récupère un système du monde
:Retourne: <Systems|None> : Système du type <classe> s'il existe
:Paramètre: <Systems> : Classe du système à récupérer

.. note:: Systems fait référence aux systèmes (EntitySystem, UISystem, MusicSystem et MusicSystem)

has_system
----------

:Description: Vérifie l'existence d'un système dans le monde
:Retourne: <bool> : Vrai si le monde a le système. Sinon Faux
:Paramètre: <Systems> : Classe du système à récupérer

.. note:: Systems fait référence aux systèmes (EntitySystem, UISystem, MusicSystem et MusicSystem)

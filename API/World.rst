World
=====

Cette classe correspond au monde d'une GameState

Constructeur
------------

:Description: Crée l'objet World
:Paramètre: Rien

Voici ces méthodes :

set_callback
------------

:Description: Définit un Callback du monde
:Retourne: Rien
:Paramètres:
    - callback <WorldCallbacks> : Callback à définir
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
:Retourne: <EntitySystem|MusicSystem|UISystem|None> : Système du type <classe> 
    s'il existe
:Paramètre: <EntitySystem|MusicSystem|UISystem> : Classe du système à récupérer

has_system
----------

:Description: Vérifie l'existence d'un système dans le monde
:Retourne: <bool> : Vrai si le monde a le système. Sinon Faux
:Paramètre: <EntitySystem|MusicSystem|UISystem> : Classe du système à récupérer


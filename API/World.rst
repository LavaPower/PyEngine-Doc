World
=====

Cette classe correspond au monde d'une GameState

Construteur
-----------

:Description: Créer l'objet World
:Retourne: Rien
:Paramètres: Rien

Voici ces méthodes :

set_callback
------------

:Description: Définis un Callback du monde
:Retourne: Rien
:Paramètres:
    - callback <WorldCallbacks> : Callback à définir
    - function <Function> : Fonction lancé au moment du callback

.. warning:: Peut retourner une exception : TypeError

get_system
----------

:Description: Récupère un système du monde
:Retourne: <EntitySystem|MusicSystem|UISystem> : Systeme du type <classe>
:Paramètre: <EntitySystem|MusicSystem|UISystem> : Classe du système à récupérer

.. warning:: Peut retourner une exception : NoSystemError

has_system
----------

:Description: Vérifie l'existence d'un système dans le monde
:Retourne: <bool> : Vrai si le monde à le système. Sinon Faux
:Paramètre: <EntitySystem|MusicSystem|UISystem> : Classe du système à récupérer


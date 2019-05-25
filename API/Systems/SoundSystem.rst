SoundSystem
===========

Cette classe correspond au système de bruitage du monde

Voici ses méthodes :

play
----

:Description: Joue un bruitage
:Retourne: Rien
:Paramètre: file <str> : Chemin vers le son

set_volume
----------

:Description: Définis le volume
:Retourne: Rien
:Paramètre: volume <int> : Volume (entre 0 et 100)

get_volume
----------

:Description: Récupère le volume
:Retourne: <int> : Volume (entre 0 et 100)
:Paramètre: Rien

get_number_sound
----------------

:Description: Récupère le nombre de sons simultanés possible
:Retourne: <int> : Nombre de sons simultanés possible
:Paramètre: Rien

set_number_sound
----------------

:Description: Définis le nombre de sons simultanés
:Retourne: Rien
:Paramètre: nb <int> : Nombre de sons simultanés possible

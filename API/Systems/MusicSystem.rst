MusicSystem
===========

Cette classe correspond au système de musique d'un monde

.. warning:: La gestion des .mp3 est un peu buggué. 
    Si votre mp3 ne fonctionne pas correctement, 
    utilisez une autre extension (exemple : .wav)

Voici ses méthodes :

next_song
---------

:Description: Passe à la musique suivante
:Retourne: Rien
:Paramètres: Rien

clear_queue
-----------

:Description: Vide la queue
:Retourne: Rien
:Paramètres: Rien

set_loop
--------

:Description: Définis si la queue se rejoue
:Retourne: Rien
:Paramètre: loop <bool> : Vrai si la queue se rejoue. Sinon faux

play
----

:Description: Lance la musique
:Retourne: Rien
:Paramètres: Rien

.. warning:: Peut retourner une exception : NoObjectError

add
---

:Description: Ajoute une musique à la queue
:Retourne: Rien
:Paramètre: file <string> : Chemin vers le fichier de la musique

set_volume
----------

:Description: Définis le volume du système
:Retourne: Rien
:Paramètre: volume <int> : Volume du système

.. note:: Le volume doit être compris entre 0 et 100

.. warning:: Peut retourner une exception : ValueError

stop
----

:Description: Arrête la musique
:Retourne: Rien
:Paramètres: Rien

pause
-----

:Description: Met en pause la musique
:Retourne: Rien
:Paramètres: Rien

unpause
-------

:Description: Relance la musique
:Retourne: Rien
:Paramètres: Rien

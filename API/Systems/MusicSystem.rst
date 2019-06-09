MusicSystem
===========

Cette classe correspond au système de musique d'un monde

.. warning:: La gestion des .mp3 est un peu bugguée. 
    Si votre mp3 ne fonctionne pas correctement, 
    utilisez une autre extension (exemple : .wav)

Voici ses attributs :

loop
----

:Description: Vrai si la queue est en mode boucle
:Type: boolean

volume
------

:Description: Volume du système
:Type: int

.. note:: Le volume doit être entre 0 et 100 sinon une erreur ValueError est lancée

Voici ses méthodes :

next_song
---------

:Description: Passe à la musique suivante
:Retourne: Rien
:Paramètre: Rien

clear_queue
-----------

:Description: Vide la queue
:Retourne: Rien
:Paramètre: Rien

play
----

:Description: Lance la musique
:Retourne: Rien
:Paramètre: Rien

.. warning:: Peut retourner une exception : NoObjectError

add
---

:Description: Ajoute une musique à la queue
:Retourne: Rien
:Paramètre: file <string> : Chemin vers le fichier de la musique

stop
----

:Description: Arrête la musique
:Retourne: Rien
:Paramètre: Rien

pause
-----

:Description: Met en pause la musique
:Retourne: Rien
:Paramètre: Rien

unpause
-------

:Description: Relance la musique
:Retourne: Rien
:Paramètre: Rien

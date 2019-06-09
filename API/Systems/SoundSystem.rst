SoundSystem
===========

Cette classe correspond au système de bruitage du monde

Voici ses attributs :

volume
------

:Description: Volume du système
:Type: int

.. note:: Le volume doit être entre 0 et 100 sinon une erreur ValueError est lancée

number_channel
--------------

:Description: Nombre de son jouable en simultané
:Type: int

Voici ses méthodes :

play
----

:Description: Joue un bruitage
:Retourne: Rien
:Paramètre: file <str> : Chemin vers le son

Lang
====

Cette classe permet de symboliser un ficher de language

Constructeur
------------

:Description: Crée l'objet Lang
:Paramètre: file <string> : Chemin vers le fichier config

.. warning:: Si le fichier n'existe pas, il retourne une ValueError

Voici son attribut :

file
----

:Description: Chemin du fichier lang
:Type: string

Voici ses méthodes :

get_translate
-------------

:Description: Retourne la traduction à partir de la clé
:Retourne: <string> : Traduction
:Paramètres: 
    - key <string> : Clé de la traduction
    - default <string> : Traduction par défaut

.. note:: Cette fonction retournera la traduction par défaut si la clé n'existe pas dans le fichier.

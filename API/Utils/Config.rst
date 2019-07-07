Config
======

Cette classe permet de symboliser un ficher de config

Constructeur
------------

:Description: Crée l'objet Config
:Paramètre: file <string> : Chemin vers le fichier config

.. note:: Si le fichier n'existe pas, il faudra utiliser la méthode create pour le créer

Voici son attribut :

file
----

:Description: Chemin du fichier config
:Type: string

Voici ses méthodes :

get
---

:Description: Retourne la valeur de la config
:Retourne: <Any> : Valeur de la config
:Paramètre: key <string> : Clé de la valeur

set
---

:Description: Définit une valeur de la config
:Retourne: Rien
:Paramètres: 
    - key <string> : Clé de la valeur
    - value <Any> : Valeur

save
----

:Description: Sauvegarde la config
:Retourne: Rien
:Paramètres: Rien

create
------

:Description: Crée la config
:Retourne: Rien
:Paramètre: dic <Dict> : Dictionnaire représentant la config

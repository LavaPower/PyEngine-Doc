Font
====

Cette classe permet de symboliser une police d'écriture

Constructeur
------------

:Description: Crée l'objet Font
:Paramètres:
    - name <string> ("Arial") : Nom de la police
    - size <int> (15) : Taille de la police
    - bold <boolean> (False) : Vrai si la police est en gras
    - italic <boolean> (False) : Vrai si la police est en italique

Voici ses attributs :

name
----

:Description: Nom de la police
:Type: string

size
----

:Description: Taille de la police
:Type: int

bold
----

:Description: Vrai si la police est en gras
:Type: boolean

italic
------

:Description: Vrai si la police est en italique
:Type: boolean

Voici ses méthodes :

renderer_size
-------------

:Description: Correspond à la taille du rendu d'un texte
:Retourne: Tuple[int, int]
:Paramètre: text <string> : Texte à rendre

__repr__
--------

:Description: Correspond à la représentation en string
:Retourne: <string>
:Paramètre: Rien

__eq__
------

:Description: Correspond à la comparaison '=='
:Retourne: <bool>
:Paramètre: <Font>

Color
=====

Cette classe permet de symboliser une couleur

Constructeur
------------

:Description: Crée l'objet Color
:Paramètres:
    - r <int> (255) : Rouge
    - g <int> (255) : Vert
    - b <int> (255) : Bleu

Voici ses méthodes :

get
---

:Description: Retourne la couleur en tuple
:Retourne: <Tuple[int, int, int]>
:Paramètre: Rien

set
---

:Description: Permet de définir une couleur
:Retourne: <Color>
:Paramètre: color <Color>

to_hex
------

:Description: Retourne la couleur en hexadécimal
:Retourne: <string>
:Paramètre: Rien

from_hex
--------

:Description: Définit la couleur à partir de l'hexadécimal
:Retourne: Rien
:Paramètre: <string>

darker
------

:Description: Retourne un couleur plus foncé
:Retourne: <Color>
:Paramètre: Rien

lighter
-------

:Description: Retourne une couleur plus clair
:Retourne: <Color>
:Paramètre: Rien

__add__
-------

:Description: Correspond à l'addition
:Retourne: <Color>
:Paramètre: <Color>

__sub__
-------

:Description: Correspond à la soustraction
:Retourne: <Color>
:Paramètre: <Color>

__repr__
--------

:Description: Correspond à la représentation en string
:Retourne: <string>
:Paramètre: Rien

__eq__
------

:Description: Correspond à la comparaison '=='
:Retourne: <bool>
:Paramètre: <Color>



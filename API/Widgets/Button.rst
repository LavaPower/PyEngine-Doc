Button
======

Cette classe permet de d'afficher un bouton.

Elle a les mêmes attributs et fonctions que Widget.
Mais elle ajoute aussi les suivants.

Constructeur
------------

:Description: Crée l'objet Button
:Paramètres:
    - position <Vec2> : Position du widget
    - text <string> : Texte sur le bouton
    - command <None|Function> (None) : Fonction lancé à l'appui du bouton
    - size <None|Tuple[int, int]> ([100, 40]) : Taille du bouton
    - image <None|string> (None) : Image du bouton

.. note:: Si l'image n'est pas spécifié, le bouton aura un rectangle gris comme fond.

Voici ses attributs :

sprite
------

:Description: Image du bouton
:Type: None ou string

size
----

:Description: Taille du bouton
:Type: Tuple[int, int]

command
-------

:Description: Fonction lancé à l'appui du bouton
:Type: None ou Function

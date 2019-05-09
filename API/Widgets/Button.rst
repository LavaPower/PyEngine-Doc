Button
======

Cette classe permet de d'afficher un bouton

Constructeur
------------

:Description: Crée l'objet Button
:Paramètres:
    - position <list> : Position du widget
    - text <string> : Texte sur le bouton
    - command <Function> (None) : Fonction lancé à l'appui du bouton
    - size <list> ([100, 40]) : Taille du bouton
    - image <string> (None) : Image du bouton

.. note:: Si l'image n'est pas spécifié, le bouton aura un rectangle gris comme fond.

get_label
---------

:Description: Récupère le label du bouton (le texte du bouton)
:Retourne: <Label> : Label du bouton
:Paramètre: Rien

.. note:: Cela permet de modifier le texte (police et couleur compris) du bouton

.. warning:: Certaines modification (notamment du contenu) peuvent entrainer
    des erreurs de placement. Pour les régler, il faut utiliser `Button.update()`

update_all
----------

:Description: Met à jour les placements du boutons et de son label
:Retourne: Rien
:Paramètre: Rien

get_size
--------

:Description: Récupère la taille du bouton
:Retourne: <list> : Taille du bouton
:Paramètre: Rien

set_size
--------

:Description: Définit la taille du bouton
:Retourne: Rien
:Paramètre: <list> : Taille du bouton

get_command
-----------

:Description: Récupère la fonction du bouton
:Retourne: <Function> : Fonction du widget
:Paramètres: Rien

set_command
-----------

:Description: Définit la fonction du widget
:Retourne: Rien
:Paramètre: <Function> : fonction du widget

get_id
------

:Description: Récupère l'id du widget
:Retourne: <int> : Id du widget
:Paramètre: Rien

.. note:: L'id vaut -1 si le widget n'a pas été ajouté à un System.

get_system
----------

:Description: Récupère le system du widget
:Retourne: <UISystem|None> : Système si le widget a été ajouté
:Paramètre: Rien

get_position
------------

:Description: Récupère la position du widget
:Retourne: <list> : Position du widget
:Paramètre: Rien

set_position
------------

:Description: Définit la position du widget
:Retourne: Rien
:Paramètre: <list> : Position du widget

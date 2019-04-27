TextComponent
=============

Cette classe permet de définir un texte à l'entité

.. warning:: Non compatible avec le SpriteComponent

Constructeur
------------

:Description: Créer l'objet TextComponent
:Retourne: Rien
:Paramètres:
    - texte <string> : Texte à afficher
    - color <list> ((255, 255, 255)) : Couleur du texte
    - font <list> (["arial", 15, False, False]) : Police du texte

.. warning:: Peut retourner une exception : CompatibilityError

.. note:: Pas de méthode utilisable avec ce composant

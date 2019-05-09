TextComponent
=============

Cette classe permet de définir un texte à l'entité

.. warning:: Non compatible avec le SpriteComponent

Constructeur
------------

:Description: Crée l'objet TextComponent
:Paramètres:
    - texte <string> : Texte à afficher
    - color <list> ((255, 255, 255)) : Couleur du texte
    - font <list> (["arial", 15, False, False]) : Police du texte

.. note:: La police est composé comme ceci : [Nom, Taille, Gras, Italique].
    Vous pouvez omettre des éléments mais seulement dans l'ordre.
    
    Exemple : Vous pouvez écrire [Nom, Taille] mais pas [Nom, Gras, Italique]

.. warning:: Peut retourner une exception : CompatibilityError

.. note:: Pas de méthode utilisable avec ce composant

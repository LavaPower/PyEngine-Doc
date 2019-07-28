Others
======

Ce fichier n'est pas une classe mais un regoupement de fonctions.

Voici ses fonctions :

clamp
-----

:Description: Force une valeur à être dans un interval
:Retourne: <int> : Valeur finale
:Paramètres:
    - val <int> : Valeur de base
    - mini <int> (None) : Valeur minimale
    - maxi <int> (None) : Valeur maximale

wrap_text
---------

:Description: Retourne le texte avec une largeur maximale
:Retourne: <str> : Texte finale
:Paramètres:
    - text <str> : Texte à wrapper
    - font <Font> : Police du texte
    - width <int> : Largeur du texte

.. note:: Cette fonction se base sur les espaces. Sans espaces, elle est inutile.

get_images_from_gif
-------------------

:Description: Récupère les frames d'un gif animé
:Retourne: <List[str]> : Liste des chemins des frames
:Paramètre: Chemin vers le gif

Console
=======

Cette classe permet d'afficher un console.

Elle a les mêmes attributs et fonctions que Widget.
Mais elle ajoute aussi les suivants.

Constructeur
------------

:Description: Crée l'objet Console
:Paramètres:
    - window <Window> : Fenetre du widget
    - position <Vec2> : Position du widget
    - width <int> : Largeur de la console

.. note:: La console a de base deux commandes :
    - print : permettant d'afficher quelque chose dans le retour
    - debug : permettant d'activer ou désactiver le debug de la fenêtre

Voici ses méthodes :

reply
-----

:Description: Affiche du texte dans le retour du widget
:Retourne: Rien
:Paramètre: texte <str> : Texte à afficher

add_command
-----------

:Description: Ajoute une commande à la console
:Retourne: Rien
:Paramètres:
    - name <str> : Nom de la commande
    - function <function> : Fonction de la commande

.. note:: Function doit avoir comme arguments : 
    - console <Console> : La console exécutant la commande
    - window <Window> : La fenêtre de jeu
    - args <List[str]> : Liste des arguments données

delete_command
--------------

:Description: Supprime une commande
:Retourne: Rien
:Paramètre: name <str> : Nom de la commande


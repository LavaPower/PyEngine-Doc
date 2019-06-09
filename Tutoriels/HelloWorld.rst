Hello World
===========

Dans ce tutoriel, nous allons créer un programme très connu : le fameux Hello World.

Grâce à ce tutoriel, vous saurez créer une fenêtre graphique 
avec un état de jeu. De plus, vous saurez utiliser le widget Label 
venant du système d'UI.

Création de la fenêtre
----------------------

La première étape est de créer la fenêtre graphique. Ici on va créer une fenêtre de 500 par 300 pixels avec un fond blanc.

Tout d'abord, il faut importer la classe de la fenêtre ainsi que de quoi utiliser les couleurs via :

.. code-block:: python

    from pyengine import Window # Window étant la classe de notre fenêtre.
    from pyengine.utils import Colors

Ensuite, il faut l'initialiser :

.. code-block:: python

    fenetre = Window(500, 300, Colors.WHITE.value)
    # 500 : Largeur
    # 300 : Longueur
    # Colors.WHITE.value : Couleur blanche

Si vous lancez ce code, vous verrez la fenêtre se lancer puis se fermer directement.

Pour régler ce problème, il faut lancer la boucle de la fenêtre. Pour cela, il suffit de faire :

.. code-block:: python

    fenetre.run()

Lancez le programme et vous devriez avoir ceci :

.. image:: images/HelloWorld1.PNG

Création du texte
-----------------

Maintenant, nous allons afficher notre texte.

Pour cela, nous allons utiliser le monde de notre fenêtre afin de récupérer le système qui gère l'ui.

.. code-block:: python

    from pyengine.Systems import UISystem

    uisystem = fenetre.world.get_system(UISystem)

Ensuite, nous devons créer notre widget et l'ajouter à notre système :

.. code-block:: python

    from pyengine.Widgets import Label
    from pyengine.Utils import Vec2

    hello = Label(Vec2(0, 0), "Hello World !", Colors.BLACK.value)
    # Vec2(0, 0) : Position x, y
    # "Hello World !" : Texte
    # Colors.BLACK.value : Couleur noire
    uisystem.add_widget(hello)

Ce qui nous donne au final :

.. code-block:: python

    from pyengine import Window, GameState
    from pyengine.Systems import UISystem
    from pyengine.Widgets import Label
    from pyengine.utils import Colors, Vec2

    fenetre = Window(500, 300, Colors.WHITE.value)

    uisystem = fenetre.world.get_system(UISystem)

    hello = Label(Vec2(0, 0), "Hello World !", Colors.BLACK.value)
    uisystem.add_widget(hello)

    fenetre.run()

Avec comme résultat :

.. image:: images/HelloWorld2.PNG

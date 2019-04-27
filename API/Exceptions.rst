Exceptions
==========

PyEngine incorpore beaucoup d'exceptions utilisées dans ses différentes classes. En voici la liste :

NoWorldError
------------

:Description: L'objet a besoin d'un monde mais ne l'a pas.
:Utilisée par: GameState

WrongComponentError
-------------------

:Description: L'objet a recu un composant n'étant pas compatible avec lui.
:Utilisée par: Entity

NoComponentError
----------------

:Description: L'objet n'a pas le composant espéré.
:Utilisée par: Entity, Pas mal de composants.

NoSystemError
-------------

:Description: L'objet n'a pas le système espéré.
:Utilisée par: World

NoGameStateError
----------------

:Description: L'objet n'a pas de GameState
:Utilisée par: Window

ComponentInitializedError
-------------------------

:Description: L'objet a eu une erreur à l'initialisation 
    (la plupart du temps, il a été initialisé deux fois)
:Utilisée par: Tous les composants

GameStateInitializedError
-------------------------

:Description: L'objet n'a pas été initialisé
:Utilisée par: GameState

CompatibilityError
------------------

:Description: L'objet n'est pas compatible avec un autre 
    objet dès mis en place.
:Utilisée par: SpriteComponent, TextComponent

NoMusicError
------------

:Description: L'objet n'a pas plus de musique à jouer
:Utilisée par: MusicSystem

EntitySystem
============

Cette classe correspond au système d'entité du monde

Voici ses méthodes :

get_entity
----------

:Description: Récupère une entité
:Retourne: <Entity|None> : Entité si elle existe ou rien.
:Paramètre: id <int> : Id de l'entité à récupérer

add_entity
----------

:Description: Ajoute une entité au système
:Retourne: <Entity> : Entité ajoutée
:Paramètre: entity <Entity> : Entité à ajouter

.. warning:: Peut retourner une exception : NoComponentError
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

.. warning:: Peut retourner une exception : NoObjectError

has_entity
----------

:Description: Savoir si une entité est enregistrée
:Retourne: <bool> : Vrai si l'entité existe
:Paramètre: entity <Entity> : Entité

remove_entity
-------------

:Description: Supprime l'enregistrement d'une entité
:Retourne: Rien
:Paramètre: entity <Entity> : Entité à supprimer

.. note:: Peut retourner une ValueError

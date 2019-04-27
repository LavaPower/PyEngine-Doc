Entity
======

Cette classe correspond à une entité votre jeu.

Construteur
-----------

:Description: Créer l'objet Entity
:Retourne: Rien
:Paramètres: Rien

Voici ces méthodes :

get_id
------

:Description: Récupère l'id de l'entité
:Retourne: <int> : Id de l'entité
:Paramètres: Rien

attach_entity
-------------

:Description: Attache une entité à notre entité
:Retourne: Rien
:Paramètre: entity <Entity> : Entity à attacher

add_component
-------------

:Description: Ajoute un composant à l'entité
:Retourne: <Components> : Composant ajouté
:Paramètres: 
    - component <Components> : Composant à ajouter
    - param <Liste> : Liste des paramètres utilisés par le composant

.. note:: Components fait référence à toutes les classes étant des composants.

.. warning:: Peut retourner une exception : WrongComponentError

has_component
-------------

:Description: Vérifie l'existance d'un composant dans l'entité
:Retourne: <bool> : Vrai si l'entité a le composant. Sinon Faux
:Paramètre: component <Components> : Composant à ajouter

.. note:: Components fait référence à toutes les classes étant des composants.

get_component
-------------

:Description: Récupère un composant de l'entité
:Retourne: <Components> : Composant dont le type est <component>
:Paramètre: component <Components> : Composant à récupérer

.. note:: Components fait référence à toutes les classes étant des composants.

.. warning:: Peut retourner une exception : NoComponentError

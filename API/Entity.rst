Entity
======

Cette classe correspond à une entité de votre jeu.

Constructeur
------------

:Description: Crée l'objet Entity
:Paramètre: Rien

Voici ses attributs :

identity
--------

:Description: Id de l'entité
:Type: int

.. note:: Le système définit l'id lui même. Elle ne doit pas être changée.

system
------

:Description: Système gérant l'entité
:Type: EntitySystem

.. note:: Le système se définit lui même. Il ne doit pas être changé.

Voici ses méthodes :

attach_entity
-------------

:Description: Attache une entité à l'entité
:Retourne: Rien
:Paramètre: entity <Entity> : Entité à attacher

add_component
-------------

:Description: Ajoute un composant à l'entité
:Retourne: <Components> : Composant ajouté
:Paramètre: component <Components> : Composant à ajouter

.. note:: Components fait référence à toutes les classes étant des composants.

.. warning:: Peut retourner une exception : TypeError

remove_component
----------------

:Description: Supprime un composant à l'entité
:Retourne: Rien
:Paramètre: component <Components> : Composant à ajouter

.. note:: Components fait référence à toutes les classes étant des composants.

.. note:: Supprimer un composant peut être dangereux. 
    Faites le que si vous n'avez pas le choix.

has_component
-------------

:Description: Vérifie l'existence d'un composant dans l'entité
:Retourne: <bool> : Vrai si l'entité a le composant. Sinon Faux
:Paramètre: component <Components> : Composant à ajouter

.. note:: Components fait référence à toutes les classes étant des composants.

get_component
-------------

:Description: Récupère un composant de l'entité
:Retourne: <Components|None> : Composant dont le type est 
    <component> s'il existe
:Paramètre: component <Components> : Composant à récupérer

.. note:: Components fait référence à toutes les classes étant des composants.

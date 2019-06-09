UISystem
========

Cette classe correspond au système d'interface utilisateur du monde

Voici ses méthodes :

add_widget
----------

:Description: Ajoute un widget au système
:Retourne: <Widgets> : Widget ajouté
:Paramètre: widget <Widgets> : Widget à ajouter

.. note:: Widgets fait référence à toutes les classes étant des widgets.

get_widget
----------

:Description: Récupère un widget au système
:Retourne: <Widgets|None> : Widget s'il existe ou rien
:Paramètre: identity <int> : Id du widget à récupérer

has_widget
----------

:Description: Savoir si un widget est enregistré
:Retourne: <bool> : Vrai si le Widget existe
:Paramètre: widget <Widgets> : Widget

.. note:: Widgets fait référence à toutes les classes étant des widgets.

remove_widget
-------------

:Description: Supprime l'enregistrement d'un widget
:Retourne: Rien
:Paramètre: widget <Widgets> : Widget à supprimer

.. note:: Widgets fait référence à toutes les classes étant des widgets.

.. note:: Peut retourner une ValueError

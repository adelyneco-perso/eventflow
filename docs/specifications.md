# Rôles

### Participant

Le participant peut :

- créer un compte ;
- se connecter ;
- consulter les événements ;
- rechercher des événements ;
- filtrer la liste ;
- afficher le détail d'un événement ;
- s'inscrire ;
- annuler son inscription ;
- consulter ses inscriptions ;
- connaître le statut de son inscription.

Un participant ne peut pas administrer un événement dont il n'est pas organisateur.

### Organisateur

L'organisateur possède toutes les possibilités d'un utilisateur classique et peut également :

- créer un événement ;
- modifier ses événements ;
- publier un événement ;
- annuler un événement ;
- consulter ses événements ;
- consulter les inscriptions ;
- consulter la liste des participants ;
- consulter la liste d'attente ;
- suivre le remplissage d'un événement ;
- accéder à un tableau de bord organisateur.

Un organisateur ne doit pouvoir modifier ou administrer que les événements dont il est propriétaire.

### Administrateur

L'administrateur possède des droits globaux sur la plateforme.

Il peut notamment :

- consulter les utilisateurs ;
- consulter tous les événements ;
- intervenir sur un événement ;
- modérer ou désactiver un événement ;
- consulter les principales données de la plateforme ;
- gérer les situations nécessitant une intervention administrative.

L'administration avancée n'est cependant pas prioritaire dans le premier MVP.

# Règles métier

- Un événement possède un organisateur.
- Seul son organisateur ou un administrateur autorisé peut le gérer.
- Seuls les événements publiés peuvent accepter normalement des inscriptions.
- Un événement annulé ne peut plus recevoir d'inscription.
- Le nombre d'inscriptions confirmées ne peut jamais dépasser la capacité.
- Lorsque la capacité est atteinte, les nouvelles inscriptions vont en liste d'attente.
- La liste d'attente suit l'ordre d'inscription.
- Lorsqu'une place se libère, la première personne en attente est promue automatiquement.
- Un utilisateur ne peut pas disposer de plusieurs inscriptions actives au même événement.
- Un utilisateur ne peut annuler que sa propre inscription, sauf privilège administratif explicite.

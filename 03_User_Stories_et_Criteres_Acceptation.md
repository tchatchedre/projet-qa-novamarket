# 03 – User stories et critères d’acceptation

## User Story 1 – Connexion

**En tant qu’** utilisateur enregistré  
**Je veux** me connecter à mon compte  
**Afin de** consulter mes informations et mes commandes

### Critères d’acceptation
- Si l’email et le mot de passe sont valides, l’utilisateur accède à son compte.
- Si un champ obligatoire est vide, un message explicite s’affiche.
- Si les identifiants sont invalides, un message d’erreur compréhensible s’affiche.
- Le bouton de connexion ne doit pas provoquer de double soumission visible.
- La page doit être utilisable au clavier.

---

## User Story 2 – Mot de passe oublié

**En tant qu’** utilisateur ayant oublié son mot de passe  
**Je veux** demander un lien de réinitialisation  
**Afin de** récupérer l’accès à mon compte

### Critères d’acceptation
- Le lien « Mot de passe oublié » doit être visible et accessible.
- Après saisie d’un email valide, un message de confirmation doit s’afficher.
- Si le format de l’email est invalide, l’utilisateur doit être guidé par un message clair.
- L’utilisateur ne doit pas être bloqué inutilement dans le parcours.

---

## User Story 3 – Qualité d’interface

**En tant qu’** utilisateur  
**Je veux** comprendre facilement les actions à réaliser  
**Afin de** terminer mon parcours sans confusion

### Critères d’acceptation
- les messages doivent être compréhensibles
- le focus clavier doit être visible
- les libellés doivent être cohérents
- les erreurs doivent aider à corriger la saisie

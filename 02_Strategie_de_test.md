# 02 – Stratégie de test

## Approche retenue

Approche de test manuel orientée risques, avec priorité sur les parcours utilisateurs les plus critiques :
1. connexion réussie
2. gestion des erreurs de saisie
3. récupération d’accès au compte
4. comportement de l’interface
5. vérifications UX / accessibilité de base

## Types de tests couverts

- tests fonctionnels
- tests de validation des champs
- tests de navigation
- tests de non-régression ciblés
- tests exploratoires légers
- vérifications d’accessibilité de premier niveau

## Priorisation

### Haute priorité
- connexion avec identifiants valides
- message d’erreur en cas de mot de passe invalide
- champ email obligatoire
- lien mot de passe oublié
- demande de réinitialisation avec email valide

### Moyenne priorité
- gestion des espaces
- comportement du bouton au double-clic
- navigation clavier
- clarté des messages
- conservation de l’email après erreur

### Basse priorité
- cohérence visuelle secondaire
- microcopie non bloquante

## Jeu de données de test

- utilisateur valide : `user.valide@novamarket.test`
- mot de passe valide : `Nova2026!`
- email invalide : `usernovamarket.test`
- email inexistant : `unknown@novamarket.test`
- champ vide : `""`

## Livrables attendus

- cas de test manuels
- rapport d’anomalies
- checklist de régression
- recommandation release

## Recommandation QA simulée

Le module peut être proposé en release **sous réserve de correction des anomalies majeures** portant sur :
- la clarté des erreurs
- le risque de double soumission
- l’accessibilité clavier

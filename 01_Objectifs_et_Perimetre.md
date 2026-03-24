# 01 – Objectifs et périmètre

## Objectifs qualité

- Vérifier que l’utilisateur peut se connecter avec des identifiants valides.
- Vérifier que les erreurs sont gérées de manière claire et utile.
- Vérifier que la fonctionnalité « mot de passe oublié » reste compréhensible.
- Réduire le risque de blocage utilisateur avant la release.
- Détecter les incohérences visibles par un utilisateur final.

## Risques identifiés

| Risque | Impact | Probabilité | Priorité |
|---|---|---:|---:|
| Impossible de se connecter avec des identifiants valides | Élevé | Moyen | Haute |
| Messages d’erreur peu clairs | Moyen | Élevé | Haute |
| Réinitialisation non comprise par l’utilisateur | Moyen | Moyen | Moyenne |
| Double soumission du formulaire | Moyen | Moyen | Moyenne |
| Problème de focus clavier / accessibilité | Moyen | Moyen | Moyenne |

## Critères d’entrée

- périmètre défini
- règles métier connues
- environnement disponible
- jeu de données de test défini

## Critères de sortie

- cas de test prioritaires couverts
- anomalies critiques remontées
- risques résiduels explicités
- recommandation QA formulée avant release

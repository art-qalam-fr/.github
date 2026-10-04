# Politique de sécurité

## Signaler une vulnérabilité

**Ne créez pas d'issue publique** pour un problème de sécurité.

Utilisez l'onglet **Security → Report a vulnerability** du dépôt concerné
(*Private Vulnerability Reporting*) ou contactez les mainteneurs directement.

Nous nous engageons à :

- Accuser réception sous 72 h
- Fournir une première évaluation sous 7 jours
- Publier un correctif ou un plan d'action sous 30 jours selon la gravité

## Périmètre

Tous les dépôts de l'organisation `art-qalam-fr`.

## Protections actives sur nos dépôts

- Secret scanning + push protection (blocage des secrets au push)
- Dependabot alerts + mises à jour de sécurité automatiques
- CodeQL (analyse statique) sur push, PR et chaque semaine
- Dependency review sur chaque pull request
- CI automatisée via GitHub Actions

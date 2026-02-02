# UC05 DevSecOps intégré

## Expression de besoin fonctionnelle
- **Objectifs** : intégrer CI/CD, sécurité et traçabilité bout‑en‑bout dans un flux unique.
- **Acteurs** : Dev, SecOps, Ops, QA.
- **Flux clés** : code → build/test → scans SAST/DAST → approvals → déploiement → traçabilité exigences.
- **Exceptions** : déploiements hotfix; dérogations contrôlées.
- **Critères d’acceptation** : pipelines standardisés, résultats de scans visibles, liens exigences→commits→releases.

## Analyse ROI
- **Gains** : réduction des défauts prod, accélération des releases, baisse du risque sécurité.
- **Coûts** : intégration outils CI/CD et scanners, licences éventuelles.
- **KPI cibles** : fréquence de déploiement, lead time changement, change failure rate, % pipelines avec scans.

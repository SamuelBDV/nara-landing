# NARA — Landing Page

Landing page statique de NARA, déployée sur **onenara.com** via **IONOS Deploy Now**.

## Structure

- `index.html` — la landing page complète (HTML/CSS/JS inline, aucune dépendance de build).

## Déploiement

Site statique pur : aucune étape de build. IONOS Deploy Now détecte le type « HTML »
et publie directement le contenu du dépôt.

Pour mettre à jour le site : modifier `index.html`, committer et pousser sur la
branche `main`. Deploy Now redéploie automatiquement.

## Contact

Le CTA « Demander une démo » ouvre un `mailto:` vers `gerald.saada@onenara.com`.
La page est bilingue FR/EN (bascule dans le header).

# NARA — Landing Page

Landing page statique de NARA, déployée sur **onenara.com** via **IONOS Deploy Now**.

## Structure

- `index.html` — landing V2 bilingue (HTML/CSS/JS inline, logo en base64).
- `og-image.png` — aperçu LinkedIn / Open Graph, 1200×630 (`https://onenara.com/og-image.png`).
- `favicon.svg` / `favicon.png` — chevron terracotta, fond transparent.

## Déploiement

Site statique pur : aucune étape de build. IONOS Deploy Now détecte le type « HTML »
et publie directement le contenu du dépôt.

Pour mettre à jour le site : modifier `index.html`, committer et pousser sur la
branche `main`. Deploy Now redéploie automatiquement.

## Contact

Le CTA « Demander une démo » ouvre un `mailto:` vers `gerald.saada@onenara.com`.
La page est bilingue FR/EN (bascule dans le header).

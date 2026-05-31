# NARA — Landing Page

Landing page statique de NARA, déployée sur **onenara.com** via **IONOS Deploy Now**.

## Structure

- `index.html` — la landing page complète (HTML/CSS/JS inline, aucune dépendance de build).

## Déploiement

Site statique pur : aucune étape de build. IONOS Deploy Now détecte le type « HTML »
et publie directement le contenu du dépôt.

Pour mettre à jour le site : modifier `index.html`, committer et pousser sur la
branche `main`. Deploy Now redéploie automatiquement.

## Modifier le formulaire de contact

Le formulaire utilise un fallback `mailto:` par défaut. Pour brancher Tally,
renseigner `TALLY_FORM_ID` dans le `<script>` en bas de `index.html`.

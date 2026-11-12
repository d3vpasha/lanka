# LANKA – site vitrine

Site vitrine de LANKA (SASU, Livry-Gargan, 93) : pose de sols durs et souples, plâtrerie, peinture intérieure et extérieure.
HTML / CSS / JS natifs, zéro build, zéro dépendance.

## Arborescence

```
index.html                      page unique (sections, sprite d'icônes inline, JSON-LD)
assets/css/styles.css           styles, variables de couleur, mode sombre
assets/js/main.js               menu mobile, apparition au défilement, formulaire WhatsApp, année
assets/img/logo.svg             logo couleur (strates + wordmark tracé)
assets/img/logo-mono-blanc.svg  logo blanc (footer, header en mode sombre)
assets/img/favicon.svg          pictogramme carré
robots.txt, sitemap.xml
```

## Lancer en local

```sh
python3 -m http.server 8000
```

## Production

https://ste-lanka.fr

## TODO

- SIREN, SIRET, code APE et lien annuaire-entreprises (après immatriculation)
- Assureur et n° de police décennale
- Valider la liste des prestations et des communes avec le client

## Versions

| Version | Date | Direction visuelle |
|---|---|---|
| v1 | 2026-11-09 | Ambiance minimal suisse sur papier pierre ; vert sauge profond + safran + beige plâtre ; hero typographique géant sur fond clair, chaque métier suivi d'une pastille-échantillon de matière (parquet, plâtre, peinture) ; engagements en ligne unique à séparateurs ; métiers en trois colonnes à grands numéros et listes à filets ; chiffres en encart latéral « En bref » ; communes en pastilles ; arrondis forts, header en pilule flottante, sans ombre ; capitales espacées ; logo trois strates en escalier + wordmark monoline tracé |

# Référentiels web — la mine d'or

Sélection de référentiels « exemplaires » (sécurité, qualité de code, qualité web,
SEO, accessibilité, écoconception, RGPD), dans l'esprit de la grille *Critères Cyber*
fournie au départ.

**Uniquement des ressources libres / sous licence ouverte ou en diffusion publique.**
Chaque ressource reste la propriété de ses auteurs et soumise à sa propre licence
(indiquée ci-dessous). Les documents « vivants » (sites web), les ouvrages commerciaux
et les pages bloquant l'aspiration automatique sont fournis en **lien** plutôt que copiés.

📋 = **grille auto-évaluable** directement réutilisable (critères en lignes, colonnes à
remplir, ou tableur) — comme la grille de départ.

---

## 01 — Sécurité applicative
- **OWASP_ASVS_5.0.0_en.pdf** 📋 — Application Security Verification Standard 5.0.0 (mai 2025), ~350 exigences / 17 chapitres. Le standard que cite la grille (« ASVS niveau 2 »).
- **OWASP_ASVS_5.0.0_en.csv** 📋 — le même contenu en CSV : à ouvrir dans un tableur, transformable en grille d'audit en quelques minutes.
  - Source : https://github.com/OWASP/ASVS · Licence : CC BY-SA 4.0
- **OWASP-CheatSheetSeries/** — 90+ fiches techniques (markdown) : auth, upload, CSP, JWT, gestion d'erreurs, etc.
  - Source : https://github.com/OWASP/CheatSheetSeries · Licence : CC BY-SA 4.0

## 02 — Données personnelles / RGPD
- **Guide-RGPD-du-developpeur-CNIL/** 📋 — guide CNIL en fiches thématiques + exemples de code.
  - Source : https://github.com/LINCnil/Guide-RGPD-du-developpeur · Licence : GPLv3 + Licence Ouverte 2.0

## 03 — Qualité web (transverse)
- **Opquast_Checklist_Qualite_Web_240_regles_FR.pdf** 📋 — 240 bonnes pratiques : perf, accessibilité, sécurité, confidentialité, SEO, écoconception, éditorial.
- **Opquast_Web_Quality_Checklist_240_EN.pdf** 📋 — version anglaise.
  - Source : https://checklists.opquast.com/fr/qualiteweb · Licence : ouverte (CC)

## 04 — Qualité de code & ingénierie
- **Google-Engineering-Practices/** — *Code Review Developer Guide* (markdown).
  - Source : https://github.com/google/eng-practices · Licence : CC BY 3.0
- **PHP-FIG-PSR/** — l'ensemble des PSR acceptées (markdown).
  - Source : https://github.com/php-fig/fig-standards · Licence : MIT

## 05 — Référencement (SEO)
- **Google_Search_Quality_Rater_Guidelines_2025-09.pdf** — 182 pages. Les critères appliqués par les évaluateurs humains de Google : E-E-A-T, YMYL (étendu en 2025), évaluation du contenu généré par IA et des AI Overviews.
  - Source : https://guidelines.raterhub.com/searchqualityevaluatorguidelines.pdf · © Google (diffusion publique)

## 07 — Écoconception / sobriété numérique
- **RGESN_2024_referentiel_78_criteres.pdf** 📋 — référentiel général d'écoconception (78 critères priorisés), avec une catégorie IA/algorithmie.
- **RGESN_2024_presentation_panorama_criteres.pdf** — présentation officielle.
- **RGESN_2024_outil_declaration_ecoconception.xlsx / .ods** 📋 — outil de déclaration (tableur officiel).
- **RGESN_2024_exemple_declaration.docx** — exemple de déclaration.
  - Source : https://ecoresponsable.numerique.gouv.fr/publications/referentiel-general-ecoconception/ · Auteurs : Arcep, Arcom, ADEME, DINUM

## 08 — Sécurité, référentiels d'État (ANSSI)
- **ANSSI_Guide_hygiene_informatique_42_mesures.pdf** 📋 — 42 mesures d'hygiène informatique.
- **ANSSI_Site_web_standards_securite_navigateur_PA-009.pdf** — recommandations site web : TLS, en-têtes de sécurité, CSP (couvre la section « chiffrement/en-têtes » de la grille).
  - Source : https://cyber.gouv.fr · Auteur : ANSSI

---

## Ressources liées (non copiées — liens)

**Sécurité** — OWASP Top 10 (https://owasp.org/Top10/) · WSTG (https://owasp.org/www-project-web-security-testing-guide/) · SAMM (https://owaspsamm.org/) · ASVS interactif (https://asvs.dev/) · SLSA (https://slsa.dev/) · CIS Benchmarks (https://www.cisecurity.org/cis-benchmarks)

**Qualité de code** — The Twelve-Factor App FR (https://12factor.net/fr/) · PER Coding Style (https://www.php-fig.org/per/coding-style/) · PHP The Right Way (https://phptherightway.com/) · Symfony Best Practices (https://symfony.com/doc/current/best_practices.html) · SemVer (https://semver.org/lang/fr/) · Conventional Commits (https://www.conventionalcommits.org/fr/) · Keep a Changelog (https://keepachangelog.com/fr/)

**SEO** — Google Search Essentials (https://developers.google.com/search/docs/essentials) · Données structurées (https://developers.google.com/search/docs/appearance/structured-data) · Schema.org (https://schema.org/) · web.dev / Core Web Vitals (https://web.dev/articles/vitals)

**Accessibilité** — RGAA 106 critères (https://accessibilite.numerique.gouv.fr/) · WCAG 2.2, à consulter en ligne, le W3C bloque l'aspiration (https://www.w3.org/TR/WCAG22/) · ARIA APG (https://www.w3.org/WAI/ARIA/apg/)

**Écoconception** — GR491 / INR (https://gr491.isit-europe.org/) · W3C Web Sustainability Guidelines (https://www.w3.org/TR/sustainable-web-design/)

**Éditorial & documentation** — Diátaxis (https://diataxis.fr/) · GOV.UK Style Guide (https://www.gov.uk/guidance/style-guide) · Microsoft Writing Style Guide (https://learn.microsoft.com/style-guide/) · Google dev doc style guide (https://developers.google.com/style) · DSFR (https://www.systeme-de-design.gouv.fr/) · Lexique des règles typographiques de l'Imprimerie nationale — ouvrage commercial (non téléchargeable)

---

## Comment t'en servir
Pour reconstituer une grille « cahier des charges » à ta main : pars du **CSV de l'ASVS**
(une ligne par exigence), ajoute les lignes pertinentes d'**Opquast** et du **RGESN**, et
conserve les colonnes *Applicable / Commentaire* de ta grille d'origine. Les guides ANSSI
et le Quality Rater servent de justification/contexte plutôt que de cases à cocher.

---
_Archive générée le 2026-06-06 09:03 UTC._

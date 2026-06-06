# Awesome Référentiels Web

> Collection curatée de référentiels publics pour concevoir, auditer et améliorer un site ou une application web — sécurité, RGPD, qualité, SEO, écoconception.

Ce dépôt rassemble, dans un format unique et facilement consultable hors ligne, les référentiels qui font autorité côté web : standards OWASP, guide RGPD de la CNIL, checklist Opquast, RGESN, guides ANSSI, etc.

**Toutes les ressources sont libres ou diffusées publiquement.** Chaque document reste la propriété de ses auteurs et soumis à sa propre licence (rappelée dans [`INDEX.md`](INDEX.md)). Les documents « vivants » (sites en ligne, ouvrages commerciaux, pages bloquant l'aspiration) sont fournis sous forme de liens plutôt que copiés.

## Pourquoi ce dépôt

- **Une seule source à parcourir** plutôt qu'une dizaine de portails officiels.
- **Hors ligne** : tout est lisible sans connexion (PDF, Markdown, tableurs).
- **Auditable** : les ressources marquées 📋 sont des **grilles auto-évaluables** prêtes à être transformées en cahier des charges ou en grille d'audit.
- **Versionné** : l'historique Git trace l'évolution des référentiels et de leurs versions.

## Sommaire

| Thème | Dossier | Référentiels phares |
|---|---|---|
| Sécurité applicative | [`01-securite-applicative/`](01-securite-applicative/) | OWASP ASVS 5.0, OWASP Cheat Sheet Series |
| Données personnelles / RGPD | [`02-donnees-rgpd/`](02-donnees-rgpd/) | Guide RGPD du développeur (CNIL) |
| Qualité web (transverse) | [`03-qualite-web/`](03-qualite-web/) | Opquast — 240 règles (FR + EN) |
| Qualité de code & ingénierie | [`04-qualite-code/`](04-qualite-code/) | Google Engineering Practices, PSR (PHP-FIG) |
| Référencement (SEO) | [`05-seo/`](05-seo/) | Google Search Quality Rater Guidelines |
| Écoconception / sobriété | [`07-ecoconception/`](07-ecoconception/) | RGESN 2024 (78 critères + outil de déclaration) |
| Sécurité — référentiels d'État | [`08-securite-etat-anssi/`](08-securite-etat-anssi/) | ANSSI — Hygiène informatique, standards web |

Le détail complet (versions, dates, licences, liens d'origine) est dans [`INDEX.md`](INDEX.md).

## Comment l'utiliser

### Lire un référentiel
Ouvrir directement le PDF, le Markdown ou le tableur dans le dossier correspondant.

### Construire un cahier des charges ou une grille d'audit
1. Partir du **CSV de l'OWASP ASVS** (une ligne par exigence).
2. Ajouter les règles pertinentes d'**Opquast** (240 règles transverses) et du **RGESN** (écoconception).
3. Conserver deux colonnes : *Applicable* (oui / non / N/A) et *Commentaire / preuve*.
4. Utiliser les guides ANSSI et le Quality Rater comme **justification et contexte**, pas comme cases à cocher.

### Cloner
```bash
git clone <url-du-depot>.git
```

## Légende

- 📋 — **Grille auto-évaluable** : critères en lignes, prête à servir d'outil d'audit.

## Licences

Chaque ressource conserve sa licence d'origine, indiquée dans [`INDEX.md`](INDEX.md). On y trouve notamment :

- **CC BY-SA 4.0** — OWASP (ASVS, Cheat Sheet Series)
- **GPLv3 + Licence Ouverte 2.0** — Guide RGPD du développeur (CNIL)
- **CC BY 3.0** — Google Engineering Practices
- **MIT** — PSR (PHP-FIG)
- **Licences ouvertes / diffusion publique** — Opquast, RGESN, ANSSI, Google Search Quality Rater Guidelines

Toute reproduction ou redistribution doit respecter la licence du document concerné.

## Contribuer

Suggestions de référentiels manquants, mises à jour de version, corrections de liens : les *issues* et *pull requests* sont bienvenues. Critères pour qu'une ressource soit acceptée :

- **Référentiel reconnu** (organisme officiel, fondation, standard de fait).
- **Diffusion libre ou publique**, avec licence claire.
- **Périmètre web** (conception, développement, exploitation, audit).

## Avertissement

Ce dépôt est une **archive de travail**. Les référentiels évoluent : vérifier la version en vigueur sur le site d'origine avant tout usage contractuel ou réglementaire.

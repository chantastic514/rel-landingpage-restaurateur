# RestoEnLigne — Landing page FR/EN — Refonte éditoriale V3

## Aperçu
Ouvrir `index.html` dans un navigateur. Le changement FR/EN, le comparateur dépliable, et le formulaire de démonstration sont fonctionnels localement.

## Direction
- Grand Hero photo, sections immersives pleine largeur et espacement généreux.
- Bénéfices avant fonctionnalités, différenciation par accompagnement humain selon le forfait.
- Le GIF réel de la plateforme est **à intégrer** à la place de `#gif-holder`. Ne montrer que les fonctions effectivement disponibles.
- Six offres dans le comparateur dépliable (incluant Entreprise) ; pas de grilles tarifaires.
- Témoignages **placeholders**, aucune citation attribuée aux restaurants. Photos d'ambiance seulement, non attribuées à ces établissements.
- Formulaire de démonstration non connecté ; remplacer par Zoho Forms/CRM.
- Remplacer `#bookings-embed` par iframe Microsoft Bookings officielle.

## SEO & GEO
- Un H1 par page ; H2 hiérarchiques ; textes HTML accessibles ; title/description ; JSON-LD Organization et WebPage.
- Pour production, demander au développeur **deux URL indexables** (par exemple `/fr/restaurateurs` et `/en/restaurants`) avec canonical et hreflang (`fr-CA`, `en-CA`, `x-default`). Le toggle JS local n'est qu'une démonstration et ne suffit pas pour un SEO bilingue robuste.
- Ajouter balises OG définitives, URL du site et image sociale ; alimenter FAQ fondées sur les vrais services si souhaité.
- Vérifier les chiffres 26 000+, 6 000+ et 2003 dans les communications REL avant publication ; ne pas présenter d'accroissement de ventes non prouvé.
- Réduire le poids des photos (WebP/AVIF, plusieurs tailles, preload hero, lazy loading hors écran), et charger le futur GIF en `video` MP4/WebM autoplay muted playsinline loop + poster pour meilleures performances.
- Offres et accompagnement à revérifier avec l'équipe REL avant mise en ligne ; les frais de 10 % sur commandes en ligne restent mentionnés dans le comparateur.

## Fichiers
- `index.html` : prototype autonome bilingue et responsive.
- `translations.json` : mêmes textes FR/EN pour intégration i18n.
- `assets/` : photos d'ambiance fournies.
- `REL_Copies_FR_EN.xlsx` : tableau de textes dans le dossier parent du ZIP et également inclus dans le ZIP.

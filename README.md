# RestoEnLigne — Landing page V4 (FR / EN)

## Démarrer
Ouvrir `fr/index.html` ou `en/index.html` via un serveur local (par exemple `python3 -m http.server 8000`). Le chemin `index.html` racine redirige vers le français. Conserver toute l’arborescence, notamment `assets/`.

## Architecture
- `fr/index.html` : version FR-CA préremplie dans le HTML (indexable même sans JavaScript)
- `en/index.html` : version EN-CA préremplie dans le HTML
- `assets/` : photos locales de la page
- `translations.json` et `REL_Copies_FR_EN_V4.xlsx` : textes source FR et EN

## Design V4
- Hero photo plein écran + bénéfice immédiat, accroche avec restaurant
- Deuxième section photo avec texte **à droite** sur desktop et à gauche sur mobile
- Solutions, GIF produit placeholder, accompagnement, comparateur 6 offres, Entreprise et témoignages placeholder
- CTA gratuit de 15 min ; bloc Microsoft Bookings et formulaire encore non connectés

## Avant production (obligatoire)
1. Mettre les chemins canonicals ABSOLUS à la vraie URL production, mettre les `hreflang` absolus et le sitemap à jour.
2. Confirmer toutes les statistiques et fonctionnalités réellement disponibles ; les offres peuvent différer selon forfait.
3. Connecter Microsoft Bookings et formulaire à Zoho / CRM, avec conformité et confidentialité.
4. Ajouter GIF de l’interface réelle ; obtenir des avis clients authentiques autorisés.
5. Vérifier performances images (formats WebP/AVIF), contrastes, responsive mobile et analytics.
6. Tenir compte des **10 % de frais de service sur les commandes en ligne** dans toute communication tarifaire détaillée.
7. Déploiement : éviter l'indexation de la V4 avant validation finale.

## GitHub
Le dépôt public contient uniquement des assets marketing ; ne pas y pousser de secrets, clés API, fichiers internes ni données de prospects. Pour donner accès à un développeur au seul dépôt, utiliser `Settings` → `Collaborators and teams` → `Add people` dans les paramètres de **ce dépôt**, puis définir l'accès approprié.

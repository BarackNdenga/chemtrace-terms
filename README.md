# ChemTrace — Conditions d’utilisation

Site statique HTML pour l’application Android ChemTrace (`com.chemtrace.app`) : Conditions d’utilisation en français (`index.html`) et reproduction en anglais de la politique de confidentialité existante (`politique-confidentialite.html`). Le document source a été retrouvé dans `BarackNdenga/PRIVACY_POLICY.md` et porte la date du 8 octobre 2026. Aucun framework, serveur, gestionnaire de paquets ou build n’est nécessaire.

## Déployer sur Vercel

1. Connectez-vous à [Vercel](https://vercel.com/) avec votre compte.
2. Choisissez **Add New → Project**, puis importez le dépôt GitHub `BarackNdenga/chemtrace-terms`. Autorisez Vercel à lire ce dépôt privé si on vous le demande.
3. Dans **Configure Project**, gardez le répertoire racine (`.`) et choisissez **Other** comme Framework Preset si Vercel ne le détecte pas automatiquement.
4. Laissez les commandes de build et le répertoire de sortie vides : il s’agit d’un site statique sans compilation. Cliquez sur **Deploy**.
5. Après le déploiement, Vercel indiquera l’adresse publique HTTPS du projet, normalement sous la forme `https://<nom-du-projet>.vercel.app`. Vérifiez la page d’accueil et le lien vers la politique de confidentialité avant d’utiliser l’URL dans Google Play Console.

Ce dépôt est préparé pour Vercel, mais le compte Vercel n’a pas été connecté et aucun déploiement n’est confirmé à ce stade. Les déploiements de production ultérieurs peuvent être déclenchés par les mises à jour de la branche `main` selon les réglages Vercel du projet.

## Fichiers

- `index.html` — Conditions d’utilisation en français, avec table des matières navigable.
- `politique-confidentialite.html` — texte existant de la politique, reproduit en anglais.
- `styles.css` — styles responsives; polices système uniquement, sans requêtes externes.
- `vercel.json` — configuration légère pour des URL propres.
- `manus-routes.json` — manifeste de routes utilisé par l’aperçu de développement.

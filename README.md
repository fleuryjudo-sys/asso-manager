# Asso Manager

Gestionnaire de tâches pour le bureau de l'association (Présidente, Secrétaire, Trésorier), avec synchronisation Supabase.

## Structure

```
index.html      → l'application (page unique)
manifest.json   → configuration PWA (icône, nom, couleurs)
sw.js           → service worker (mode hors-ligne)
icons/          → icônes de l'application
```

## Déploiement

Voir les instructions détaillées fournies avec ce projet pour :
1. Publier ce dossier sur GitHub
2. Le déployer sur Vercel (déploiement automatique à chaque `git push`)

## Configuration

Le nom de l'association se change dans `index.html`, recherchez :
```js
assoName: 'Notre Association',
```

Les mots de passe des 3 comptes (Anaïs, Gabrielle, Antoine) se changent dans `index.html`, recherchez :
```js
const ASSO_USERS = [ ... ]
```

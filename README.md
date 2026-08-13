# Lucas France Travel — site vitrine

Site statique en un seul fichier (`index.html`, HTML/CSS/JS inline, aucune dépendance de build).

## Déploiement rapide (Git + Netlify)

```bash
# 1. Dans le dossier du site
git init
git add .
git commit -m "Site initial"

# 2. Créer un repo vide sur GitHub (via le site), puis :
git remote add origin https://github.com/<votre-user>/lucas-france-travel.git
git branch -M main
git push -u origin main
```

Ensuite sur [app.netlify.com](https://app.netlify.com) :
1. "Add new site" → "Import an existing project" → autoriser GitHub.
2. Choisir le repo `lucas-france-travel`.
3. Build command : laisser vide. Publish directory : `.` (racine).
4. Déployer — chaque `git push` sur `main` redéploiera automatiquement.

## Formulaire de contact

Le formulaire utilise `data-netlify="true"`, Netlify le détecte automatiquement au déploiement.
Les soumissions apparaissent dans Site settings → Forms sur votre dashboard Netlify.
Pensez à activer une notification email (Forms → Settings → Form notifications) pour être alerté à chaque nouveau contact.

## Nom de domaine personnalisé

Une fois `lucasfrancetravel.com` acheté (Namecheap, Google Domains, etc.) :
Site settings → Domain management → Add a custom domain, puis suivre les instructions DNS de Netlify.

## Prochaines retouches faciles

- Remplacer les 3 exemples d'itinéraires par de vrais voyages que vous avez planifiés.
- Ajuster la fourchette de prix dans la section `#pricing`.
- Ajouter de vraies photos une fois disponibles (actuellement le site est volontairement sans photo, en style éditorial/typographique).

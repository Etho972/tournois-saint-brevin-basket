# Tournois Saint-Brevin Basket

Plateforme réutilisable pour créer et gérer des tournois de basket : inscriptions des clubs par lien, planning multi-terrains avec échauffement, résultats en temps réel, classements automatiques et phases finales adaptatives.

## Espace organisateur

- Ouvrir `/admin.html`
- Entrer le mot de passe défini dans la variable d’environnement `ADMIN_PASSWORD` de la fonction Supabase `admin`.
- Créer un tournoi, valider les équipes, générer le planning, saisir les scores, attribuer arbitres et table, générer les phases finales.

## Variables Supabase

- `ADMIN_PASSWORD` : mot de passe organisateur (à définir dans les secrets de la fonction Edge).
- `SUPABASE_URL` et `SUPABASE_SERVICE_ROLE_KEY` sont fournis automatiquement aux Edge Functions.
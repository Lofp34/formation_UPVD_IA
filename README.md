# Matrice d’adaptation relationnelle — application apprenant

Application web statique, responsive et sans compte utilisateur, conçue pour la formation UPVD IN CUBE animée par Laurent Serre Développement.

## Fonctionnalités

- découverte des 4 styles relationnels : Structurer, Décider, Explorer, Coopérer ;
- outil d’observation rapide avec hypothèses de profil dominant et secondaire ;
- conseils immédiats d’adaptation ;
- quiz et cas pratiques ;
- adaptation du pitch ;
- plan d’action personnel enregistré localement dans le navigateur ;
- fonctionnement hors connexion via service worker.

## Déploiement

Application statique : aucun build, aucune variable d’environnement. Compatible Vercel, GitHub Pages et autres hébergements statiques.

## Données

Aucune donnée n’est envoyée à un serveur. Le plan d’action est stocké uniquement dans le navigateur via `localStorage`.

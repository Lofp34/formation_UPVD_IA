# Matrice d’adaptation relationnelle — application apprenant

Application web statique, responsive et sans compte utilisateur, conçue pour la formation UPVD IN CUBE animée par Laurent Serre Développement.

## Fonctionnalités

- découverte des 4 styles relationnels : Structurer, Décider, Explorer, Coopérer ;
- outil d’observation rapide à 12 critères ;
- hypothèses de profil dominant et secondaire ;
- conseils immédiats d’adaptation ;
- quiz et cas « interlocuteur difficile » ;
- génération de 4 angles de pitch ;
- plan d’action personnel enregistré localement dans le navigateur.

## Déploiement

Application statique : aucun build et aucune variable d’environnement. Le dépôt contient `index.html`, `styles.css`, `app.js` et `vercel.json` et peut être déployé directement sur Vercel.

## Données

Aucune donnée n’est envoyée à un serveur. Le plan d’action est stocké uniquement dans le navigateur via `localStorage`.

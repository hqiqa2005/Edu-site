# Petits Explorateurs

Site éducatif Astro + TypeScript pour les enfants de 6 à 11 ans.

## Démarrage local

```bash
npm install
npm run dev
```

Puis ouvrir l'adresse indiquée par Astro.

## Production

```bash
npm run build
```

Le projet est prêt à être importé dans GitHub puis déployé sur Vercel.

## Structure

- `src/data/software.ts` : catalogue des activités
- `src/pages/index.astro` : accueil
- `src/pages/logiciels/` : catalogue et pages individuelles
- `src/pages/parents.astro` : espace adultes de démonstration
- `src/styles/global.css` : charte graphique responsive

## Ajouter une activité

Ajouter un objet dans `src/data/software.ts`. Les pages individuelles sont générées automatiquement.

## À faire avant une vraie mise en production

- connecter les boutons « Jouer » et « Télécharger » aux logiciels réels ;
- ajouter un vrai CMS/admin si nécessaire ;
- ajouter les mentions légales et la politique de confidentialité définitives ;
- mettre en place les mécanismes de consentement et de protection des mineurs nécessaires au contexte réel ;
- connecter éventuellement un nom de domaine `.ma`.

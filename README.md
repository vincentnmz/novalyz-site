# Site vitrine Novalyz

www.novalyz.fr · Astro (site statique) · publié par GitHub Actions sur la branche `gh-pages`.

- Réglages (textes des boutons, statut bêta, e-mail, éditeur) : `src/config/site.ts`
- Développer : `npm ci` puis `npx astro dev` · Construire : `npx astro build`
- Chaque push sur `main` republie le site.
- Le formulaire `/beta` envoie à l'action publique `inscriptionBeta` du serveur de l'app (Supabase).

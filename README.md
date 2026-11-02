# Life RPG

Turn your daily habits into an RPG — quests, XP, weekly bosses, and rewards.

A single-file web app (`index.html`) backed by Supabase. No build step —
just static files served as-is.

## Live site

This repo is set up to deploy automatically via **GitHub Pages** whenever
you push to the `main` branch. Once enabled (see below), your site will be
available at:

```
https://<your-github-username>.github.io/<this-repo-name>/
```

## Deploying / updating

1. Push your changes to `main` (or upload files directly on GitHub — see
   the setup guide).
2. GitHub Pages rebuilds automatically within a minute or two. No build
   command, no CI pipeline — it just serves the files directly.

## Database

This app talks directly to Supabase from the browser (no server, no
backend code in this repo). Database schema and migrations are tracked
separately and are not part of this repo's deployment.

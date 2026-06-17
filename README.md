# Sample PWA MVP

Minimal two-page progressive web app for install testing on Android and iPhone.

## Deploy to Vercel

This project is ready for a static Vercel deploy.

### Option 1: Vercel dashboard

1. Create a new GitHub repo and put the files from this folder in it.
2. Go to Vercel and click `Add New -> Project`.
3. Import that GitHub repo.
4. Keep the default settings.
5. Click `Deploy`.

### Option 2: Vercel CLI

If you have Node installed:

```bash
npm install -g vercel
vercel
```

Run `vercel` inside this folder and accept the defaults.

After deploy, open the HTTPS Vercel URL on Android Chrome and check the browser menu for `Install app`.

## Run locally

You need a local web server because service workers do not run from `file://`.

If Python is available:

```bash
python3 -m http.server 4173
```

Then open `http://localhost:4173`.

## Install testing

- Android Chrome: open the site and look for the install prompt or browser install option.
- iPhone Safari: use Share -> Add to Home Screen.

## Note

I could not read `defter_prd_v1_2.pdf` because this environment does not support PDF input.

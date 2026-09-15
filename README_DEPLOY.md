# Fincline — production static site for Vercel

This package is ready to deploy as a static website. No build command, Node.js runtime, or environment variables are required.

## Package contents
- `index.html` — homepage
- `styles.css` — site styles
- `assets/` — Fincline logo, favicon, hero image, and custom illustrations
- `vercel.json` — clean URL / static hosting configuration

## Recommended first deployment: Vercel Drop
1. Go to https://vercel.com/drop
2. Drag `fincline-vercel-site.zip` onto the page.
3. Choose the correct Vercel account/team.
4. Name the project `fincline` (or your preferred project name).
5. Click **Deploy**.
6. Open the generated `.vercel.app` URL and verify the site.
7. In the project, open **Settings → Domains** and add your Fincline domain when ready.

Important: Vercel Drop creates a new project for each drop. For ongoing updates, connect the deployed project to Git or use the Vercel CLI.

## If you already have a Fincline Vercel project
Use Git integration or the Vercel CLI instead of Drop.

### Vercel CLI
From the unzipped `fincline-vercel-site` folder:

```bash
npm i -g vercel
vercel login
vercel link
vercel --prod
```

During `vercel link`, select the existing Fincline Vercel project.

## Recommended ongoing workflow
1. Put these files in a GitHub repository.
2. In Vercel, import/connect that repository to the Fincline project.
3. Future pushes to the production branch will deploy automatically.

## Before final public launch
- Confirm the `12–20 hrs/week` to `10-minute review` performance claim is a claim you want to publish.
- Confirm `hello@fincline.com` is the correct contact address.
- Add the final Fincline domain under Vercel project **Settings → Domains**.
- After the domain is known, add canonical / social metadata if desired.

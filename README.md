# BREW DISTRICT — Coffee Shop Website

Original responsive React + Vite coffee shop website with an urban specialty-coffee identity.

## Run locally
1. Install Node.js LTS.
2. Open this folder in VS Code or a terminal.
3. Run `npm install`.
4. Run `npm run dev` and open the local URL Vite prints.

## Production
Run `npm run build`. Vite creates the production site in `dist/`.

## Deploy with GitHub + Vercel
1. Upload the contents of this folder to a GitHub repository. Keep `package.json` and `index.html` at the root; keep `main.jsx` and `styles.css` inside `src/`.
2. In Vercel choose **Add New → Project** and import the repository.
3. Use Framework **Vite**, Build Command `npm run build`, Output Directory `dist`.
4. Deploy. Future commits trigger automatic deployments.

## Before using for a real café
Replace the sample address, contact details, hours and menu prices. The map link is a generic Quezon City search. The newsletter form is frontend-only and does not store addresses or send emails; connect a backend or mailing service before collecting customer information. Images load from Unsplash and require internet access.

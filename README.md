# ZK Mood Ring

Vite (vanilla) dev setup for the ZK Mood Ring demo.

Commands:

- `npm run dev` - start dev server (http://localhost:5173)
- `npm run build` - build production files to `dist/`
- `npm run preview` - preview production build locally

Vercel deployment

- A `vercel.json` config file is included for Vercel.
- To enable automatic deploys on push, connect this repository to Vercel (https://vercel.com) and set the GitHub repository.
- If you prefer deploying via GitHub Actions, this repository includes `.github/workflows/deploy-vercel.yml` that runs on push to `main` and deploys via `amondnet/vercel-action`.

To use the GitHub Actions deploy, add these repository secrets in GitHub:
- `VERCEL_TOKEN` — a personal token from Vercel (can be created in Vercel dashboard).
- `VERCEL_ORG_ID` — your Vercel organization id.
- `VERCEL_PROJECT_ID` — your Vercel project id.

Notes:
- Vite builds the site to `dist/` by default; the workflow runs `npm run build` before deploying.
- If you prefer Vercel's native Git integration (recommended), simply connect the repo in the Vercel dashboard and set build command to `npm run build` and output directory to `dist/`.

# ZK Mood Ring — Dynamic PFP NFTs for Emotional Web3

A lightweight Proof of Concept for the **Endless Ecosystem Creative Proposal Competition**.

> 🧠 *AI-generated NFT avatars that reflect your emotional state — verified by ZK-proof, without revealing content.*

---

## ✅ Demo  
🔗 Live demo:  
https://zk-mood-ring.vercel.app/

> 💡 Built with pure HTML/CSS/JS — no backend, no smart contracts.

---

## 🌟 Features

- 🔗 Connect social accounts: Luffa, GitHub, X  
- 🧠 AI analyzes mood from activity patterns  
- 🔐 ZK-proof verifies emotional state (e.g., “happy”, “sly”, “excited”)  
- 🎨 PFP NFT (256×256) dynamically updates expression:  
  - 😊 Happy  
  - 😏 Sly *(default)*  
  - 🤩 Excited  
  - 😌 Relaxed  
- 🛡️ Privacy-first: only mood state on-chain — no messages, no posts, no metadata leak.

---

## 🎯 Value to Endless Ecosystem

- ✅ **Humanizes Web3** — brings emotional authenticity back to interactions  
- ✅ **Enhances social layer** — mood-aware dApps (e.g., DAO voting weight, matchmaking)  
- ✅ **Drives engagement** — users personalize & share their “mood journey”  
- ✅ **Aligns with “Everyday Web3”** — simple, expressive, owned by the user.

---

## 🛠️ Tech Stack

- Frontend: HTML/CSS/JS (no framework)  
- Hosting: GitHub Pages  
- Future: Integrate with Endless DID + real ZK circuits (e.g., Circom for mood aggregation)

---

## 📬 Submit Info

- **Proposal Title**: `ZK Mood Ring: AI-Generated NFT Avatars That Reflect Your Emotional State`  
- **Demo Link**: `https://zk-mood-ring.vercel.app/`  
- **GitHub Repo**: `https://github.com/duchth1993/zk-mood-ring`  
- **Category**: `Fill a Gap`  
- **Inspiration**: `AI Agent Social/Tool Application`
  
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


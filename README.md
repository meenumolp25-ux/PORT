PM Vikas Portfolio — Deployment

This repository is a static personal portfolio site. Use one of the options below to deploy to Vercel.

Option A — Deploy via GitHub (recommended)
1. Create a GitHub repository and push this project (root contains `index.html`).
2. Go to https://vercel.com/import and import the GitHub repo.
3. Choose the root directory and deploy (no build step required).

Option B — Deploy using Vercel CLI
1. Install Vercel CLI:

```bash
npm install -g vercel
```

2. From the project root, login and deploy:

```bash
vercel login
vercel --prod
```

Option C — Quick local preview
If you just want to preview locally, you can open `index.html` in your browser or run a simple static server:

```bash
# using Python 3
python -m http.server 8000
# then open http://localhost:8000
```

Notes
- `vercel.json` is included to instruct Vercel to serve the static site.
- If you want, I can create a GitHub repo and push the project, then connect it to Vercel for you — grant access or provide details if you want me to proceed.

# DecMD — Interactive Clinical Network Showcase

**Live application:** Open the GitHub Pages URL for this repository (Settings → Pages), not this README.

The application starts at **`index.html`** in the repository root. It is a synthetic, browser-only demonstration of the DecMD clinical workspace for the InnoLab 2026 pitch.

## Features

- Clinical overview; patient/family roster; four source institutions and detailed records
- Lab intelligence, glucose unit normalization and trend visualization
- Evidence-explained record connections and interactive clinical constellation
- Longitudinal timeline and hospital network
- Clinical conflict review, donation documentation, browser-session activity, and retrieval workflow

## Publish from a new GitHub repository

1. Extract the ZIP. Upload the **contents**, not an enclosing folder, to a new repository. Ensure `index.html` appears at the repository root.
2. Open **Settings → Pages** → **Deploy from a branch** → `main` → `/(root)` → **Save**.
3. Open `https://YOUR_USERNAME.github.io/YOUR_REPO/` after publication succeeds.

From the extracted folder using Git:

```bash
git init
git branch -M main
git add .
git commit -m "Publish DecMD interactive pitch showcase"
git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO.git
git push -u origin main
```

## Data and security boundary

**This is a static, synthetic-data showcase.** No real patient data, login/authentication, backend, hospital retrieval, PostgreSQL, cryptographic verification, source approvals, or persistent tamper-evident audit logs are implemented here. Decisions and activity in the UI are illustrative and browser-session only. The separate Flask codebase is required for the backend.

No backend keys or private credentials are included. D3.js is bundled locally for reliable loading.

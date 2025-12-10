## AR-slavicin

Simple image-tracking AR demo using Three.js and MindAR.

The app is a single-page web app at `index.html`. Open it via a local server (camera access requires a secure origin: HTTPS or `http://localhost`).

**Quick start**

Requirements:
- Node.js and npm (optional)

1. Install dependencies (optional — only required if you want the bundled `http-server`):

```bash
npm install
```

2. Start the local server:

```bash
npm start
```

3. Open your browser at `http://localhost:8080` and click the **Start** button in the page to grant camera access. Then point your camera at the target image (there's a link to the example target image in the UI).

Notes:
- The project includes a lightweight `http-server` dev dependency used by the `start` script in `package.json`.
- Browsers require a secure origin for camera access. Use `http://localhost` for local testing or serve the site over HTTPS.
- If you don't want to install deps, you can run a quick static server with `npx http-server ./ -p 8080`.

Assets removed:
- `kostka.glb` and `marker-image.jpg` were not referenced by `index.html` and have been removed to keep the repo minimal.

Publishing:
- If you publish the repo with GitHub Pages (branch `main`, root), the demo will be available at `https://<your-user>.github.io/AR-slavicin/` and will run over HTTPS.

License: MIT

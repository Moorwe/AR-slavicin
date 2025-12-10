## AR-slavicin

WebXR AR demo using Three.js. Place virtual objects on detected surfaces using your device's camera.

The app is a single-page web app at `index.html`. Open it via a local server or published URL (HTTPS required for camera access).

**Quick start**

Requirements:
- ARCore/ARKit capable device (Android with Chrome, or iOS with Safari)
- Node.js and npm (optional, for local testing)

1. Install dependencies (optional):

```bash
npm install
```

2. Start a local server:

```bash
npm start
```

3. Open your browser at `http://localhost:8080`. Click the **AR Button** to start the AR session. Move your device to detect surfaces, then tap to spawn objects.

**Supported Browsers:**
- Chrome on Android (requires ARCore support)
- Safari on iOS 14+ (requires ARKit support)

Notes:
- The project uses `http-server` as a lightweight dev dependency.
- Browsers require HTTPS or `localhost` for camera access due to security policies.
- The app uses WebXR with hit-testing to detect and place objects on real-world surfaces.
- If you don't have Node.js, use `npx http-server ./ -p 8080`.

Publishing:
- Deploy to GitHub Pages (branch `main`, root) for a public HTTPS URL: `https://<user>.github.io/AR-slavicin/`
- The site will run over HTTPS and prompt for camera permission when the AR Button is clicked.

License: MIT

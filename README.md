# AR-slavicin
This repository demonstrates a simple AR image-tracking demo using MindAR and Three.js.

The demo is a single-page web app found at `index.html`. To enable camera access in your browser, serve the project via localhost (camera access requires HTTPS or `http://localhost`).

## Usage

1. Install dependencies:

```bash
npm install
```

2. Start the local server:

```bash
npm start
```

3. Open your browser at `http://localhost:8080` and click the "Start" button to grant camera access. Then show the target image (link in the UI) to the camera.

## Notes
- Uses `http-server` (dev dependency in `package.json`) for a simple local server
- Camera access requires `http://localhost` or a secure origin (HTTPS) in modern browsers
- If you want to change port, update the `start` script in `package.json`

## GitHub Pages / Published URL
If you publish this repository via GitHub Pages (branch `main`, root), the demo will be available at:

`https://Moorwe.github.io/AR-slavicin/`

The site should load over HTTPS and will prompt for camera access when you click the Start button.

## Pulling the latest changes
If you've made edits in the web editor and/or pushed changes to the `main` branch, update your local copy by running:

```bash
git pull origin main
```

If you want to test the local copy on a machine, run `npm install` and `npm start` to serve the repo over `http://localhost:8080`.

## License
MIT
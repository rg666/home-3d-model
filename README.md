# RaRe home 3D

An interactive 3D model of our 2.5 BHK flat for trying out interior ideas: orbit, top view, walk-through, room-by-room paint and flooring, and saved designs.

Open `index.html` in any modern browser, or visit the GitHub Pages link for this repository.

## How it works
- Everything runs in the browser. There is no server and nothing to install.
- `app.js` contains the 3D engine (three.js, MIT licence) and the app code, bundled into one file.
- Designs you make are saved in your own browser (localStorage). They are not shared with other visitors, and they are lost if you clear your browser data.

## Host it on GitHub Pages
1. Create a new public repository on GitHub, for example `rare-home-3d`.
2. Upload `index.html`, `app.js`, `.nojekyll` and this README to the repository root (Add file > Upload files).
3. Go to Settings > Pages, set Source to "Deploy from a branch", choose `main` and `/ (root)`, and save.
4. After a minute or two the site is live at `https://<your-username>.github.io/rare-home-3d/`.

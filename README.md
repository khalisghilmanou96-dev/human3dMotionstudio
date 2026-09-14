# Human Motion Studio — KGStudio

Copyright © 2026 KGStudio. All Rights Reserved.

This repository is prepared for static hosting with GitHub Pages.

## License

This project is **proprietary software**. Public access to the repository or
hosted application does not grant permission to copy, modify, redistribute,
resell, sublicense, or create derivative works.

See the `LICENSE` file for the complete terms.

# Human Motion Studio

Static browser-based 3D motion prototype featuring:

- Forward walk
- Backward walk
- Smooth left/right U-turns
- Smooth 90° left/right turns
- Continuous gait through turns
- Thin triangulated body mesh
- 3D camera controls
- REC / STOP / PLAY
- Timeline
- 3D JSON import/export

The character remains still when idle: no automatic breathing or torso motion.

## GitHub Pages

This repository is ready to be hosted directly with GitHub Pages.

1. Create a new GitHub repository.
2. Upload the contents of this folder to the repository root.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select the `main` branch and `/ (root)` folder.
6. Save.

GitHub will provide the public Pages URL after deployment.

## Local preview

```bash
python3 -m http.server 8020
```

Then open:

```text
http://localhost:8020/
```

## Files

- `index.html` — complete application; no build step required.
- `.nojekyll` — tells GitHub Pages to serve the static files directly.
- `LICENSE` — MIT license for this prototype code.

# Practice Metronome

An offline-capable metronome PWA with audio, vibration (where supported), flashing beats, pendulum, and tempo presets.

## GitHub Pages

1. Create a GitHub repository (for example `metronome`).
2. Put these files in the repository root and commit them to `main`.
3. Open Settings > Pages > Build and deployment.
4. Select Deploy from a branch, `main`, `/(root)`, then Save.
5. Visit `https://YOUR-USERNAME.github.io/metronome/`.

Install from Chrome's menu on Android or Safari's Share > Add to Home Screen on iPad.

The HTML, manifest, and service-worker URLs are relative, so deployment under a repository path works without editing them.

For offline use, visit the hosted site once while online and allow the service worker to install. When changing cached application files, increment `CACHE` in `sw.js` to invalidate older cached assets.

Vibration support depends on device/browser settings and may be disabled by Do Not Disturb.

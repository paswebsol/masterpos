# Master POS — GitHub Pages deployment

## Deploy
1. Extract this ZIP.
2. Create a GitHub repository (or open your existing client-app repository).
3. Upload **all files and the `icons` folder** from this package to the repository root. Keep the folder structure.
4. In GitHub, open **Settings → Pages**.
5. Under Build and deployment, select **Deploy from a branch**, choose your branch (usually `main`) and folder `/ (root)`, then Save.
6. Wait for GitHub Pages to publish. Share the published URL ending in `/repository-name/` with clients. The root `index.html` opens the app directly.

## Client installation
- Android: open the link in Chrome and use the visible **Install App** button.
- iPhone/iPad: open the link in Safari → Share → Add to Home Screen. iOS may not show a programmatic install prompt.
- Windows/macOS/Linux: open in a supported Chrome/Edge browser and use **Install App** or the browser's install icon/menu.
- The app remains usable in the browser if installation is unavailable.

## Important
- Install prompts are controlled by the browser; a website cannot force an installation without the client's confirmation.
- PWA installation requires HTTPS, which GitHub Pages provides.
- The service worker caches the app shell for offline loading after the first successful online visit.
- Keep the license issuer and client app paired as intended. Each browser profile/device may produce a different installation ID.

# SSG TALAAN Portal — Installable App Build

This package turns the supplied fixed TALAAN frontend into an installable Progressive Web App (PWA).

## Backend
The supplied Google Apps Script backend is not modified. The existing Apps Script Web App endpoint remains the frontend's API bridge.

## Install
1. Deploy this folder to HTTPS hosting (GitHub Pages is suitable).
2. Open the deployed site in Chrome/Edge on Android or a supported browser.
3. Use the browser's **Install app / Add to Home screen** option.
4. Launch **SSG TALAAN** from the home screen for the standalone app experience.

## Important
- Camera/QR scanning still requires browser/OS camera permission.
- Network access is required for Google Sheets / Apps Script operations.
- The service worker caches the app shell but deliberately does not cache Apps Script API responses.
- The original supplied TALAAN HTML/logic was retained; only PWA metadata and service-worker registration were added.

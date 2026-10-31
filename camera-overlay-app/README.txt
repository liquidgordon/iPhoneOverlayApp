CAMERA OVERLAY — iPHONE WEB APP

This is a private-use web app (no App Store or Apple developer subscription needed).
It does not upload or save photos. It runs entirely in your browser.

INSTALL THROUGH FREE GITHUB PAGES
1. Sign in to github.com and create a new PUBLIC repository (e.g. camera-overlay).
2. Upload all the files from this folder to the root of the repository, keeping their names.
3. In the repository, select Settings > Pages.
4. Under Build and deployment, choose Deploy from a branch, then main and /(root), and Save.
5. Wait for GitHub to show the site address in Settings > Pages.
6. On your iPhone, open that HTTPS address in Safari.
7. Tap Share > Add to Home Screen, then Add (enable Open as Web App if shown).
8. Open your new home-screen icon and tap Start camera. Allow camera access.
9. Tap Choose photo to select a picture from Photos. Use the opacity slider.

IMPORTANT
- The website URL and the app's source code will be publicly accessible on free GitHub Pages.
  Your selected photos and camera video are NOT uploaded or sent to GitHub.
- Camera access requires an HTTPS site; opening index.html directly from a local file
  may not work as expected on iPhone.
- When in standalone home-screen mode, iOS may ask for camera permission again on
  subsequent launches.
- The app includes a service worker to cache its files for offline launches after
  visiting the site online at least once. Camera permissions are still controlled by iOS.
- iPhone device testing has not been done; the files are an initial implementation.

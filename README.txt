GUEST COUNTER - INSTALL AND USE

This is a small, offline-capable Progressive Web App (PWA) for Android.

FEATURES
- Include/exclude each family with a checkbox (counts preserved)
- Adjust adults and children independently
- See totals for adults, children, and combined guests
- Add/edit/delete families and their preset counts
- Reset Counts restores all preset counts (without changing checkbox selections)
- Select All and Clear All
- Automatic local saving on this device
- Works offline after initial visit and successful service-worker installation

QUICK DESKTOP PREVIEW
Open index.html in a browser. It works and saves your changes, but offline installation
requires hosting over HTTPS.

INSTALL ON ANDROID (RECOMMENDED: GITHUB PAGES)
1. Create a public GitHub repository, such as guest-counter.
2. Upload all files from this folder to the repository root.
3. In repository Settings -> Pages, choose Deploy from a branch, main, /(root).
4. Visit the resulting https://YOUR-USERNAME.github.io/guest-counter/ URL in Chrome on Android.
5. Use Chrome menu -> Add to Home screen -> Install (wording may vary).
6. Launch the Guest Counter icon; it will work offline after caching.

DATA/PRIVACY
All data stays in the browser storage on the device. No account, server database, or
cloud sync. If you clear the browser's site data or uninstall and clear app data,
your family list and counts may be lost. Different browsers/devices have separate data.

The sample family names are placeholders; edit/delete them as needed.

ZCE BILLING APP

Files:
- index.html: billing app
- manifest.json: installable web app settings
- sw.js: offline cache support

Quick use:
1. Open index.html in a modern browser to use the basic app locally.
2. To install as an app and enable proper offline caching, publish these three files to a free HTTPS static host (for example GitHub Pages).
3. Open the published HTTPS address in Chrome and choose Install app / Add to Home Screen.

Important data note:
Bills and products are stored in browser local storage on the current device/browser. They do not automatically sync between devices or browsers. Use Bill History > Export Backup regularly and keep the JSON backup safe. Import Backup restores it on another device. Online hosting does not itself create cloud sync.

PDF:
Use Download / Print PDF, then choose Save as PDF in the print dialog.

No paid service or account is required for the local app. Free hosting availability and terms are controlled by the hosting provider.

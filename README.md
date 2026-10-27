# Ang Sinag PWA demo

## Run locally
Open `index.html` in a browser. For installable PWA/service-worker behavior, serve this folder over HTTPS or localhost, for example:
`python -m http.server 8000`

Then open `http://localhost:8000`.

## Included
- Responsive Home, News Top Stories, Feature Stories, Editorial Cartooning, and Admin CMS views
- Article detail pages with title, image, byline, date, full story, and photo caption
- Add/edit/delete content and JSON export
- PWA manifest and basic service worker
- Placeholder copy and sample images

## Important limitations
- This is a front-end demonstration. CMS changes are stored in the current browser's localStorage and are not shared between editors/devices.
- It has no authentication, hosted database, server-side upload, or multi-user permissions. Do not publish private data or treat the demo CMS as a secure production admin panel.
- Sample articles are placeholders and must be replaced with fact-checked stories and properly credited/permissioned images.
- Google Fonts and remote sample images need internet access. The basic page shell is cached by the service worker after first load.

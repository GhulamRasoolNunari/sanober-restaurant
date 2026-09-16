SANOBER RESTAURANT PWA - INTEGRATED VERSION

Upload all files to the same public/root directory as index.html.

The original index.html has been preserved and its existing UI/scripts remain.
PWA fixes made:
- Replaced the broken data:application/manifest+json link with ./manifest.json
- Added proper PWA icons and Apple touch icon links
- Added service-worker registration
- Kept the existing Install banner and improved its install handling
- Replaced the banner placeholder "a" with the Sanober logo
- Added a versioned service worker that clears old caches

Requirements:
- Production: HTTPS is required for service workers/PWA installation.
- Local testing: localhost is allowed.
- Do not test by opening index.html directly with file://.

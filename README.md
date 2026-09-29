# get-ssd.github.io

Beta landing page for SSD (Signed, Sealed, Delivered), served by GitHub Pages at
https://get-ssd.github.io/.

## What's here

- `index.html` is the whole site: one static page with inline CSS and no build step.
  - A mock feed showing Tick's badges. The badge CSS is copied from `ssd-tick-2/ui/styles.css`.
  - Feature summary and download links.
- `favicon.ico` and `icon-192.png` are copied from the PWA.

## Links the page depends on

- App (PWA): https://get-ssd.github.io/SignedSealedDelivered/ (Pages on `get-ssd/SignedSealedDelivered`)
- Tick downloads: `https://github.com/get-ssd/ssd-tick-2/releases/latest/download/ssd-tick-firefox.xpi`
  and `.../ssd-tick-chrome.zip`. Every Tick release must attach assets with exactly these names.

## Status

Beta. The Firefox build is unsigned; Firefox Nightly is the tested platform, and it's required
on Android. Chrome is installed by hand with "Load unpacked".

## Deploying

Push to `master`. Pages serves the repo root.

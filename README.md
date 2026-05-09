# Young & Brooks Website Prototype

This is a static, dependency-free website build based on the Google Stitch direction in the parent folder.

## Security posture

- No runtime JavaScript.
- No third-party analytics, trackers, ad pixels, iframes, or remote fonts.
- No remote images. The hero image is stored locally in `assets/`.
- Restrictive Content Security Policy is present in `index.html`.
- Vercel security headers are configured in `vercel.json`.
- Static-host security headers are also provided in `_headers` for hosts that support that file format.

## Local preview

Open `index.html` directly in a browser, or run a static server from this folder:

```sh
python3 -m http.server 4173
```

Then visit `http://localhost:4173`.

QA screenshots are saved in `qa/` for the checked desktop and mobile viewports.

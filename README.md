# BD Photo & Signature Studio

A privacy-first browser editor for Bangladesh job applications.

## Smart tools
- AI portrait background removal (browser-side model)
- One-click auto-enhance for brightness, contrast and colour
- Rotate 90°, horizontal flip, fit/fill framing
- Photo and signature modes with common pixel presets and custom dimensions
- Signature paper cleanup and automatic empty-margin trimming
- White, light blue, soft green, grey and transparent backgrounds
- JPG, PNG and WebP export; adjustable quality and optional target file-size compression
- Responsive interface; images are edited locally in the browser

**Important:** Presets are examples, not official universal requirements. Check each recruitment circular or portal for exact dimensions, file format, file-size limit and background rules. Review the final image carefully. Auto-enhancement and signature trimming are automatic estimates and may need manual review.

## Run locally
Serve this folder over HTTP, for example: `python -m http.server 8000`, then open `http://localhost:8000`.

## GitHub Pages
Open Settings → Pages → Deploy from a branch, select `main` and `/(root)`, then Save.

## Privacy
The original image is not uploaded to an application server. Background-removal model files and the editor's JavaScript module are fetched from a CDN. Google Fonts are also loaded externally.

## Stack
HTML · CSS · JavaScript ES modules · Canvas API · @imgly/background-removal

# BD Photo & Signature Studio

A browser-based image editor tailored for Bangladesh job applications, recruitment portals and admission forms.

## Features
- Photo and signature editing modes
- Common application presets: 300×300, 300×400, 600×600, 600×800, 300×80 and 600×160 pixels
- Custom output dimensions
- AI background removal using the browser-side @imgly/background-removal package
- White, light blue, soft green, grey and transparent photo backgrounds
- Signature paper cleanup for light backgrounds
- Brightness, contrast and saturation adjustments
- JPG, PNG and WebP export with adjustable quality
- Responsive desktop and mobile interface
- Local image editing; uploaded originals are not sent to an application server

> Presets are convenient common sizes, not a guarantee of requirements for every Bangladesh employer or recruitment portal. Always check the specific job circular or application instructions before submitting.

## Run locally
Serve this folder over HTTP because the background-removal library is loaded as an ES module. For example, run: python -m http.server 8000
Then visit http://localhost:8000.

## Deploy with GitHub Pages
1. Open Settings → Pages.
2. Under Build and deployment, choose Deploy from a branch.
3. Select main and /(root), then Save.
4. Wait for the Pages deployment to finish.

You can also deploy this static site to Vercel.

## Privacy
Photo editing and export happen in the user's browser. The AI background-removal package downloads its model from its CDN on first use; the source photo is processed client-side. Google Fonts and the JavaScript package/model are third-party network dependencies.

## Technology
HTML · CSS · JavaScript ES modules · Canvas API · @imgly/background-removal

---
Built for Bangladesh applicants.
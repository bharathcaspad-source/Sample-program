# React Site for Cloudflare Pages

## Local development
npm install
npm run dev

## Build
npm run build
(outputs to the "dist" folder)

## Deploy to Cloudflare Pages
1. Push this project to a GitHub repo (recommended), or use direct upload.
2. Go to Cloudflare Dashboard > Workers & Pages > Create > Pages.
3. Connect your GitHub repo (or choose "Upload assets" and upload the dist folder after building).
4. Build settings:
   - Framework preset: Vite
   - Build command: npm run build
   - Build output directory: dist
5. Deploy. Cloudflare will give you a live URL like yourproject.pages.dev.

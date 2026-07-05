# LeadHunter Digital Dashboard HTTPS Deploy Package

This folder is ready to deploy as a static HTTPS dashboard.

## Fastest options

### Netlify Drop
1. Go to `https://app.netlify.com/drop`.
2. Drag this whole `https-deploy-package` folder into Netlify.
3. Netlify will create an HTTPS URL like `https://example-name.netlify.app`.
4. Rename the site or attach a custom domain in Netlify settings.

### Vercel
1. Create a new Vercel project.
2. Upload/import this folder.
3. Use framework preset: `Other`.
4. Output directory: leave blank.
5. Vercel will create an HTTPS URL.

### Cloudflare Pages
1. Create a Pages project.
2. Upload this folder.
3. Build command: leave blank.
4. Output directory: `/`.
5. Cloudflare will create an HTTPS URL.

## Investor note

The current local `file://` URL only works on the machine that created it.
Once deployed, the investor must use the HTTPS URL from the hosting provider.


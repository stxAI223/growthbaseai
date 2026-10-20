# Growth Base AI

Static website for Growth Base AI, deployed on Vercel.

## Files
- `index.html` — the site (single file, no build step)
- `founder.jpg` — founder photo used in the About section
- `favicon.svg`, `favicon.ico`, `apple-touch-icon.png`, `icon-192.png`, `icon-512.png` — icons
- `og-image.png` — social share preview (1200×630)
- `logo.svg`, `logo.png`, `logo-light-bg.svg` — logo files for use elsewhere
- `vercel.json` — clean URLs, caching and security headers

## Deploy
1. Push this repo to GitHub.
2. In Vercel, click **Add New → Project**, import the repo, leave all settings default, deploy.
3. Add your domain under **Settings → Domains**.

## Editing
- Copy and layout live in `index.html`. Search for `Sample` to find the demo results section; replace the quotes and numbers with real ones and delete the `<span class="sample">` tag.
- Colors are CSS variables at the top of the `<style>` block.

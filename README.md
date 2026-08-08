# Websters4u — Static Site

Plain HTML site, no build step required. All pages are linked to each
other with relative paths, so keep every file in this same folder.

## Files
- `index.html` — homepage
- `portfolio-clothing.html`
- `portfolio-salon.html`
- `portfolio-dental.html`
- `portfolio-realestate.html`
- `portfolio-restaurant.html`

## Deploy to Vercel

### Option A — Vercel CLI (fastest)
1. Install the CLI if you don't have it: `npm i -g vercel`
2. From inside this folder, run:
   ```
   vercel
   ```
3. Follow the prompts (link/create a project). No build command or
   output directory needed — Vercel auto-detects this as a static site.
4. Run `vercel --prod` when you're ready to publish the production URL.

### Option B — GitHub + Vercel dashboard
1. Push this whole folder to a new GitHub repo (keep all files at the
   repo root, or in one subfolder — just be consistent).
2. Go to vercel.com → **Add New Project** → import the repo.
3. Leave the framework preset as **Other** / static — no build command
   needed.
4. Deploy.

### Option C — Drag and drop
1. Go to vercel.com → **Add New Project**.
2. Drag this entire folder (not a single file) onto the upload area.
3. Deploy.

## After deploying
Your links will resolve automatically, e.g.:
```
yoursite.vercel.app/
yoursite.vercel.app/portfolio-clothing.html
yoursite.vercel.app/portfolio-salon.html
```

No code changes needed — the relative links already point to the
correct filenames.

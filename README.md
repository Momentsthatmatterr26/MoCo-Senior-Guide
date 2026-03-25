# Moments That Matter — MoCo Senior Care Guide

## Files in this folder

| File | Description |
|---|---|
| `index.html` | Landing page (your website) |
| `guide.pdf` | The senior care guide PDF |
| `logo.jpg` | Moments That Matter logo |
| `keira.jpg` | Keira's photo |

## How to set up on GitHub + Netlify

### Step 1 — Add your files
Copy these files into this folder:
- `guide.pdf` — rename your PDF to exactly `guide.pdf`
- `logo.jpg` — rename the logo image to exactly `logo.jpg`
- `keira.jpg` — rename Keira's photo to exactly `keira.jpg`

### Step 2 — Create a GitHub repository
1. Go to github.com → click **New repository**
2. Name it (e.g. `moco-senior-guide`)
3. Set to **Public** or **Private** (both work with Netlify)
4. Upload all files in this folder to the repo

### Step 3 — Connect to Netlify
1. Go to app.netlify.com → **Add new site** → **Import an existing project**
2. Choose **GitHub** and authorize Netlify
3. Select your repository
4. Leave build settings blank (no build command, no publish directory)
5. Click **Deploy site**

### Step 4 — Set your custom domain name
1. In Netlify dashboard → **Domain settings**
2. Click **Change site name** → type something like `momentsthatmatter`
3. Your site will be live at: `momentsthatmatter.netlify.app`

## How to update the PDF later
1. Replace `guide.pdf` in your GitHub repo with the new version (keep the same filename)
2. Commit the change
3. Netlify redeploys automatically — same URL, updated content

## Need a custom domain? (e.g. momentsthatmatter.com)
Purchase a domain from any registrar (Namecheap, Google Domains, etc.)
then in Netlify → Domain settings → Add custom domain.

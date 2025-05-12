# BrainWorkHub Static Site

This is a static version of your Framer site, ready for deployment on Vercel.

## Structure

- `index.html` — main page with sections and navigation.
- `style.css` — basic styling for layout and typography.
- `images/` — place your illustrations here:
  - `home.png`
  - `easywork.png`
  - `mindwork.png`
  - `digitaltool.png`
  - `blogs.png`
  - `faq.png`

## Deployment

1. Push this folder to your GitHub repository:
   ```bash
   git init
   git add .
   git commit -m "Initial static site export"
   git branch -M main
   git remote add origin <YOUR_REPO_URL>
   git push -u origin main
   ```
2. On Vercel, import the repository and select:
   - **Framework Preset:** Other – Static Site
   - **Output Directory:** `./`

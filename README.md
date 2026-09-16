# Freddy's Roofing — Sales Preview

This is a **sales preview** website prepared for Freddy's Roofing LLC (Glendale / Phoenix West Valley, AZ).

It is **not** an official site published by the business. It is a demonstration preview for sales outreach.

## Pages

- `index.html` — Home
- `services.html` — Services
- `about.html` — About
- `reviews.html` — Customer reviews
- `contact.html` — Contact / free estimate

## Preview notice

Every page includes a banner stating this is a preview and not yet published by the business.

## GitHub Pages Setup

**Manual setup required:** Due to GitHub API permissions, Pages must be enabled manually in repository settings.

### Steps to enable the live site:

1. Go to https://github.com/rutmehta/freddys-roofing-preview/settings/pages
2. Under **Build and deployment**:
   - **Source**: Select "GitHub Actions" from the dropdown
3. Click **Save**
4. Wait 1-2 minutes for the workflow to deploy

Once enabled, the site will be live at: **https://rutmehta.github.io/freddys-roofing-preview/**

The GitHub Actions workflow (`.github/workflows/deploy-pages.yml`) will automatically deploy any future changes pushed to the `main` branch.

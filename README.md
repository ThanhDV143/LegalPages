# LegalPages — Google OAuth website starter

Static pages for Google Auth Platform > Branding > App domain:
- `index.html` — Application home page
- `privacy.html` — Privacy Policy
- `terms.html` — Terms of Service
- `style.css` — Responsive styling

## Before publishing
Replace all bracketed placeholders (`[APP_NAME]`, `[DEVELOPER_NAME]`, `[DATA_COLLECTION]`, etc.) and `CONTACT_EMAIL` with truthful app-specific information. Remove publisher checklists from the public pages. Do not submit incomplete templates for OAuth verification.

Google OAuth permissions, data collection, data retention and sharing must reflect the actual app. The provided policies are editable starting points, not finalized legal documents.

## GitHub Pages
Repository: https://github.com/ThanhDV143/LegalPages

Go to **Settings > Pages > Build and deployment**, select **Deploy from a branch**, choose **main** and **/(root)**, then Save.

Once deployment is live, the expected page addresses are:
- Home: https://thanhdv143.github.io/LegalPages/
- Privacy: https://thanhdv143.github.io/LegalPages/privacy.html
- Terms: https://thanhdv143.github.io/LegalPages/terms.html

Verify every URL in a browser before putting it into Google Cloud Console. You might also need to verify ownership of an authorized domain in Search Console; a custom domain may be required for OAuth app verification.

GitHub Pages docs: https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site
Google docs: https://support.google.com/cloud/answer/13464321?hl=en

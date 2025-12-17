# Eggus Landing Page

Professional landing page for Eggus iOS app, designed for OAuth provider approval and VC presentations.

## Files Included

- `index.html` - Main landing page
- `privacy.html` - Privacy Policy (required for OAuth)
- `terms.html` - Terms of Service (required for OAuth)
- `logo.png` - App icon/logo
- `favicon.png` - Browser favicon

## Deployment to GitHub Pages

1. **Upload files to your GitHub repository:**
   ```bash
   # In your local eggus.io repository
   git add index.html privacy.html terms.html logo.png favicon.png README.md
   git commit -m "Add landing page with privacy policy and terms"
   git push origin main
   ```

2. **GitHub Pages will automatically deploy** (already configured)

3. **Wait for DNS propagation** (5 minutes to 1 hour)

4. **Verify:**
   - Visit https://eggus.io
   - Check https://eggus.io/privacy.html
   - Check https://eggus.io/terms.html

## For OAuth Setup

Use these URLs when registering with OAuth providers:

- **LinkedIn Developer Console:** https://www.linkedin.com/developers/
  - Redirect URL: `https://eggus.io/auth/callback`
  - Privacy Policy: `https://eggus.io/privacy.html`
  - Terms of Service: `https://eggus.io/terms.html`

- **Facebook Developer Console:** https://developers.facebook.com/
  - Redirect URL: `https://eggus.io/auth/callback`
  - Privacy Policy: `https://eggus.io/privacy.html`
  - Terms of Service: `https://eggus.io/terms.html`

- **Instagram (via Facebook):** Same as Facebook

## Design Notes

- Clean, minimalist design matching app aesthetic
- Dark blue gradient background (#1e3a5f to #2d5a7b)
- Fully responsive (mobile-friendly)
- Professional tone (trust & seriousness)
- No dating/flirting vibe (as per brand strategy)

## Contact Emails Referenced

Update these in the HTML files once you have your official contact addresses:
- `contact@eggus.io` (general inquiries)
- `privacy@eggus.io` (privacy questions)
- `legal@eggus.io` (legal/terms questions)

## Future Enhancements

- Add email collection for launch waitlist
- Add App Store badge when live
- Add screenshots/demo video
- Integrate analytics (Google Analytics)

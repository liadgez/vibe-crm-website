# VibeCRM Website Deployment Guide

## Files Created
- `index.html` - Homepage with privacy policy link
- `privacy-policy.html` - Complete privacy policy page
- This deployment guide

## Deployment Options

### Option 1: GitHub Pages (Recommended)
1. Create a new repository called `vibe-crm-website` on GitHub
2. Upload both HTML files to the repository
3. Go to Settings → Pages
4. Select "Deploy from a branch" and choose "main"
5. Your site will be available at `https://yourusername.github.io/vibe-crm-website/`

### Option 2: Netlify (Free)
1. Go to [netlify.com](https://netlify.com)
2. Drag and drop the `/Users/liadgez/Documents/vibe-crm-website/` folder
3. Your site will get a random URL like `https://random-name.netlify.app`
4. You can connect a custom domain `vibe-crm.com` in settings

### Option 3: Vercel (Free)
1. Go to [vercel.com](https://vercel.com)
2. Import the folder or connect to GitHub
3. Deploy and connect your custom domain

### Option 4: Custom Domain Setup
If you already own `vibe-crm.com`:
1. Upload files to your hosting provider's root directory
2. Ensure `index.html` is in the root
3. Ensure `privacy-policy.html` is accessible at `/privacy-policy.html`

## Testing URLs
After deployment, verify:
- Homepage: `https://vibe-crm.com/`
- Privacy Policy: `https://vibe-crm.com/privacy-policy.html`

## Google OAuth Update
Once deployed, update your Google Cloud Console with:
- Homepage URL: `https://vibe-crm.com`
- Privacy Policy URL: `https://vibe-crm.com/privacy-policy.html`

## Next Steps
1. Deploy the website
2. Test both URLs are accessible
3. Update Google Cloud Console OAuth settings
4. Reply to the verification email confirming fixes
# Deployment Guide

## GitHub Pages Deployment

Follow these steps to deploy your RK Industries website on GitHub Pages:

### 1. Enable GitHub Pages

1. Go to your repository settings: https://github.com/pandeysarthak023-crypto/R.K.industries-website/settings
2. Scroll down to **Pages** section
3. Under "Source", select:
   - Branch: `main` (or your default branch)
   - Folder: `/ (root)`
4. Click **Save**

### 2. Access Your Website

Your site will be live at:
```
https://pandeysarthak023-crypto.github.io/R.K.industries-website/
```

## Custom Domain (Optional)

If you want to use a custom domain:

1. In GitHub Pages settings, add your custom domain
2. Update your DNS records at your domain registrar
3. Point your domain to GitHub Pages

### DNS Configuration
If using a custom domain like `rkindustries.com`:
- **A Record**: Point to GitHub's IP addresses
- **CNAME Record**: Point to `pandeysarthak023-crypto.github.io`

## Maintenance

To make updates:
1. Edit `index.html` or other files
2. Commit and push to main branch
3. GitHub Pages automatically rebuilds within minutes

## Performance Tips

- The site is already optimized with:
  - Tailwind CSS (via CDN)
  - Font Awesome icons (via CDN)
  - Responsive design
  - Fast load times

## Testing

Before deploying updates:
1. Open `index.html` locally in your browser
2. Test all links and buttons
3. Check responsiveness on mobile devices
4. Verify WhatsApp links work correctly

---

**Your website is now live and ready to reach customers!**

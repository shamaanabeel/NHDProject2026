# GitHub Pages Deployment Guide

## Quick Start (3 Easy Steps)

### Step 1: Commit and Push Your Files
```bash
git add .
git commit -m "Set up GitHub Pages with CSS, JS, and Jekyll"
git push origin main
```

### Step 2: Enable GitHub Pages
1. Go to: https://github.com/mnabeel/shamaa/settings/pages
2. Under "Source", select: **main** branch
3. Keep folder as: **/ (root)**
4. Click: **Save**

### Step 3: Wait and Visit
- Wait 1-2 minutes for deployment
- Visit: https://mnabeel.github.io/shamaa
- You should see a green checkmark when ready!

## What's Included

? **index.html** - Main homepage with hero section, features, and stats
? **about.html** - About page template
? **css/style.css** - Beautiful, modern styling with animations
? **js/script.js** - Interactive features (smooth scroll, counters, etc.)
? **_config.yml** - Jekyll configuration
? **Gemfile** - Ruby dependencies for local development
? **.gitignore** - Ignore unnecessary files

## File Structure
```
shamaa/
??? index.html          ? Main page
??? about.html          ? About page
??? css/
?   ??? style.css       ? All your styles
??? js/
?   ??? script.js       ? Interactive features
??? _config.yml         ? Jekyll config
??? Gemfile             ? For local testing
??? .gitignore          ? Git ignore rules
??? README.md           ? Documentation
??? DEPLOY.md           ? This file
```

## Features

### CSS Features:
- Responsive design (mobile, tablet, desktop)
- Smooth animations and transitions
- Modern gradient backgrounds
- Card-based layouts
- Dark mode support
- Sticky navigation header

### JavaScript Features:
- Smooth scrolling navigation
- Animated counters for statistics
- Intersection Observer for scroll animations
- Dynamic header shadow on scroll
- Theme toggle support
- Developer console messages

### Jekyll Features:
- SEO optimization
- Sitemap generation
- RSS feed support
- Easy theme switching

## Customization Tips

### Change Site Title/Description
Edit `_config.yml`:
```yaml
title: Your New Title
description: Your new description
```

### Change Colors
Edit `css/style.css`:
```css
:root {
    --primary-color: #YOUR_COLOR;
    --secondary-color: #YOUR_COLOR;
}
```

### Update Stats Numbers
Edit `index.html` - find the stats section and change `data-target` values:
```html
<span class="stat-number" data-target="500">0</span>
```

### Add New Pages
1. Create new HTML file (e.g., `contact.html`)
2. Copy structure from `about.html`
3. Add link to navigation in all pages

## Testing Locally (Optional)

If you want to test Jekyll locally before deploying:

1. **Install Ruby** (if not installed)
2. **Install dependencies**:
   ```bash
   gem install bundler
   bundle install
   ```
3. **Run local server**:
   ```bash
   bundle exec jekyll serve
   ```
4. **Visit**: http://localhost:4000/shamaa

## Troubleshooting

### Site not showing up?
- Check Settings ? Pages for deployment status
- Make sure branch is set to "main" and folder is "/ (root)"
- Wait a few minutes - first deployment can take 5-10 minutes

### CSS/JS not loading?
- Clear your browser cache
- Check that file paths are correct (case-sensitive on GitHub)
- View page source to verify file references

### Jekyll theme not working?
- Make sure `_config.yml` is committed
- Check GitHub Pages build logs in repository Actions tab
- Try using `theme: minima` for a built-in theme

## Next Steps

1. ? Customize the content in `index.html`
2. ? Update `about.html` with your project details
3. ? Change colors in `css/style.css`
4. ? Add your own images to an `images/` folder
5. ? Create additional pages as needed
6. ? Set up a custom domain (optional)

## Resources

- **GitHub Pages Docs**: https://docs.github.com/en/pages
- **Jekyll Docs**: https://jekyllrb.com/docs/
- **Markdown Guide**: https://www.markdownguide.org/
- **CSS Reference**: https://developer.mozilla.org/en-US/docs/Web/CSS

---

Good luck with your National History Day project! ??

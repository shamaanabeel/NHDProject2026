# Shamaa

National History Day project - A beautiful GitHub Pages website

## ?? Features

- **Modern Design**: Clean, responsive layout with smooth animations
- **Interactive Elements**: JavaScript-powered counters and smooth scrolling
- **Jekyll Integration**: Easy content management with Jekyll static site generator
- **Mobile Friendly**: Fully responsive design that works on all devices
- **Dark Mode Support**: Automatic dark mode based on system preferences

## ?? Live Demo

Visit the live site at: [https://mnabeel.github.io/shamaa](https://mnabeel.github.io/shamaa)

## ?? Project Structure

```
shamaa/
??? index.html          # Main HTML file
??? css/
?   ??? style.css       # Custom styles
??? js/
?   ??? script.js       # JavaScript functionality
??? _config.yml         # Jekyll configuration
??? Gemfile             # Ruby dependencies
??? .gitignore          # Git ignore rules
??? README.md           # This file
```

## ??? Setup Instructions

### Option 1: GitHub Pages (Recommended)

1. **Enable GitHub Pages**:
   - Go to repository Settings ? Pages
   - Set Source to `main` branch
   - Select `/ (root)` folder
   - Click Save

2. **Wait for deployment** (1-2 minutes)

3. **Visit your site** at `https://mnabeel.github.io/shamaa`

### Option 2: Local Development with Jekyll

1. **Install Ruby** (2.5.0 or higher)
   
2. **Install dependencies**:
   ```bash
   gem install bundler
   bundle install
   ```

3. **Run locally**:
   ```bash
   bundle exec jekyll serve
   ```

4. **Visit** `http://localhost:4000/shamaa`

## ?? Customization

### Change Colors
Edit `css/style.css` and modify the CSS variables:
```css
:root {
    --primary-color: #0366d6;
    --secondary-color: #6f42c1;
    /* ... other colors ... */
}
```

### Update Content
- Edit `index.html` to change text, sections, and layout
- Modify `_config.yml` for site settings

### Add New Pages
Create new HTML files in the root directory and link to them in the navigation.

## ?? Using Jekyll Themes

Uncomment and choose a theme in `_config.yml`:
```yaml
theme: minima
# or
remote_theme: pages-themes/cayman@v0.2.0
```

Supported themes: minima, cayman, slate, midnight, architect, leap-day, and more.

## ?? Contributing

This is a personal project, but suggestions are welcome! Feel free to:
- Report issues
- Suggest improvements
- Submit pull requests

## ?? License

This project is open source and available under the MIT License.

## ?? Links

- **Repository**: [github.com/mnabeel/shamaa](https://github.com/mnabeel/shamaa)
- **GitHub Pages**: [pages.github.com](https://pages.github.com)
- **Jekyll Documentation**: [jekyllrb.com](https://jekyllrb.com)

---

Built with ?? for National History Day

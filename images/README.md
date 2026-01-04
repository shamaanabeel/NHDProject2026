# Images Directory

This directory contains all images used throughout the Scientific Revolution documentary website.

## Directory Structure

```
images/
??? thesis/
?   ??? galileo-heroes.jpg (or .png)
?   ??? copernicus-matejko-1873.jpg (or .png)
??? revolution/
??? reform/
??? reaction/
??? impacts/
??? discoveries/
??? people/
```

## Image Guidelines

### File Naming Convention
- Use lowercase letters
- Separate words with hyphens
- Include year or artist name when relevant
- Example: `copernicus-matejko-1873.jpg`

### Image Formats
- **Preferred:** JPG for photographs and paintings
- **Alternative:** PNG for images requiring transparency
- **Optimize:** Keep file sizes under 500KB for web performance

### Image Sizes
- **Hero images:** 1200px wide minimum
- **Content images:** 800-1000px wide
- **Thumbnails:** 300px wide

## Attribution

All images should include proper attribution in the figcaption elements on the website.

### Required for Thesis Section:

1. **Honor Galileo and the Heroes of the Scientific Revolution**
   - Location: `images/thesis/galileo-heroes.jpg`
   - Description: A tribute to the pioneers of the Scientific Revolution

2. **Astronomer Copernicus, or Conversations with God**
   - Location: `images/thesis/copernicus-matejko-1873.jpg`
   - Artist: Jan Matejko
   - Year: 1873
   - Description: Copernicus contemplating his heliocentric model

## Sources for Public Domain Images

### Recommended Sources:
- **Wikimedia Commons:** https://commons.wikimedia.org
- **Library of Congress:** https://www.loc.gov/pictures/
- **National Gallery of Art:** https://www.nga.gov/open-access-images.html
- **The Met Collection:** https://www.metmuseum.org/art/collection

### Search Tips:
1. Search for "Scientific Revolution" + artist name
2. Look for "Public Domain" or "CC0" licenses
3. Check image resolution (minimum 1000px)
4. Download highest quality available

## How to Add Images

1. Download the image from a public domain source
2. Rename according to naming convention
3. Optimize if larger than 500KB
4. Place in appropriate subdirectory
5. Update the HTML file to reference the image:

```html
<img src="images/thesis/copernicus-matejko-1873.jpg" 
     alt="Astronomer Copernicus by Jan Matejko" 
     style="width: 100%; height: auto; border-radius: 5px;">
```

## Copyright & Attribution

- All images must be public domain or properly licensed
- Include artist name and year in figcaption
- Link to source when possible
- Respect copyright laws and fair use guidelines

## Image Optimization Tools

- **TinyPNG:** https://tinypng.com/ (compress JPG/PNG)
- **Squoosh:** https://squoosh.app/ (Google's image optimizer)
- **ImageOptim:** https://imageoptim.com/ (Mac)

---

**Note:** Currently using placeholders. Replace with actual images before final deployment.

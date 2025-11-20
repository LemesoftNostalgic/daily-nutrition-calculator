# Daily Nutrition Calculator

A web-based nutrition calculator that helps you plan your daily meals and calculate monthly grocery costs.

## Image Files

The application now supports multiple image formats for body type visualizations:
- JPG/JPEG
- PNG
- WebP
- SVG

### How to Replace Images

To use your own realistic photos instead of the current SVG illustrations:

1. Prepare 9 images representing different body types:
   - 60kg-sedentary
   - 60kg-moderate
   - 60kg-active
   - 75kg-sedentary
   - 75kg-moderate
   - 75kg-active
   - 90kg-sedentary
   - 90kg-moderate
   - 90kg-active

2. Save them in the `images/` folder with the naming format:
   - `60-sedentary.jpg` (or .png, .webp)
   - `60-moderate.jpg`
   - `60-active.jpg`
   - `75-sedentary.jpg`
   - `75-moderate.jpg`
   - `75-active.jpg`
   - `90-sedentary.jpg`
   - `90-moderate.jpg`
   - `90-active.jpg`

3. The application will automatically detect and load the images in order of preference: JPG → PNG → WebP → SVG

### Image Sources

You can find appropriate body type images from:
- **Unsplash** (unsplash.com) - Free high-quality photos
- **Pexels** (pexels.com) - Free stock photos
- **Pixabay** (pixabay.com) - Free images
- Search terms: "fitness body types", "athletic person", "body composition"

### Image Requirements

- Recommended dimensions: 200-400px width
- Aspect ratio: Portrait orientation (approximately 1:2)
- File size: Keep under 200KB each for fast loading
- Background: Preferably plain or minimal background
- Subject: Androgynous or neutral representation showing full body

The application includes fallback behavior - if an image is not found, it will display a friendly error message indicating which image file is missing.

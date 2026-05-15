# TOSHU Studio - Landing Page

Premium static landing page for TOSHU Studio, an automotive video content agency.

## Technical Details
- Built strictly with HTML5, CSS3, and Vanilla JavaScript.
- No external libraries, no frameworks, no dependencies (No React, No jQuery, No Bootstrap).
- Fully responsive across mobile, tablet, and desktop environments.
- High-end dark theme aesthetic with custom smooth scrolling, intersection observers for scroll animations.
- **GoHighLevel (GHL) Calendar Integration:** Embedded directly for automated audit booking.
- **Wistia Video Preparation:** Built-in CSS architecture in `.hero-video-card` to support 16:9 Wistia video embeds seamlessly.

## Local Development & Preview
To run the website locally and preview the animations and layout:
1. Open your terminal.
2. Navigate to the project directory: `cd "path/to/toshu-automotive-landing anti gravity"`
3. Start a local Python server: `python3 -m http.server 8000`
4. Open your browser and visit: [http://localhost:8000](http://localhost:8000)

## Deployment Instructions

Because this is a completely static, vanilla web project, it can be deployed for free on modern hosting platforms in seconds. It is currently configured for automated deployment via GitHub to Vercel.

### Vercel Deployment (Current Workflow)
1. Any changes pushed to the `main` branch of this GitHub repository will automatically trigger a new Vercel build.
2. Images are served directly from the root directory for optimized relative linking.
3. Live Site URL is managed via the Vercel Dashboard.

## Folder Structure
- `index.html`: Main landing page structure, SEO tags, GHL Calendar embed, and content.
- `style.css`: All styling, CSS variables, GHL iframe formatting, Wistia iframe formatting, and responsive media queries.
- `script.js`: Smooth scroll navigation (with 64px header offset calculation) and IntersectionObserver fade animations.
- `*.jpg` / `*.png`: Visual assets (logos, hero backgrounds, and portfolio images) stored directly in the root directory for optimized path resolution.
- `README.md`: This documentation file.

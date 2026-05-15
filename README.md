# TOSHU Studio - Landing Page

Premium static landing page for TOSHU Studio, an automotive video content agency.

## Technical Details
- Built strictly with HTML5, CSS3, and Vanilla JavaScript.
- No external libraries, no frameworks, no dependencies (No React, No jQuery, No Bootstrap).
- Fully responsive across mobile, tablet, and desktop environments.
- High-end dark theme aesthetic with custom smooth scrolling, intersection observers for scroll animations, and a dynamic mailto form handler.

## Local Development & Preview
To run the website locally and preview the animations and layout:
1. Open your terminal.
2. Navigate to the project directory: `cd "path/to/toshu-automotive-landing anti gravity"`
3. Start a local Python server: `python3 -m http.server 8000`
4. Open your browser and visit: [http://localhost:8000](http://localhost:8000)

## Deployment Instructions

Because this is a completely static, vanilla web project, it can be deployed for free on modern hosting platforms in seconds.

### Deploying to Netlify (Recommended)
1. Log in to [Netlify](https://app.netlify.com/).
2. Go to **Sites** and click **Add new site** > **Deploy manually**.
3. Drag and drop the entire `toshu-automotive-landing anti gravity` folder directly into the deployment zone.
4. Netlify will instantly build and serve your static `index.html` file.
5. You can set up your custom domain (toshustudios.com) in the "Domain Management" settings.

### Deploying to Vercel
1. Log in to [Vercel](https://vercel.com/).
2. Click **Add New** > **Project**.
3. You can either deploy via linking a Git repository or using the Vercel CLI.
4. For CLI deployment:
   - Install Vercel CLI (`npm i -g vercel`).
   - Navigate to your project directory in the terminal.
   - Run `vercel` and follow the prompts.
5. Leave all settings as default (Framework preset: "Other").
6. Connect your custom domain in the project settings.

## Folder Structure
- `index.html`: Main landing page structure, SEO tags, and content.
- `style.css`: All styling, CSS variables, and responsive media queries.
- `script.js`: Smooth scroll navigation, IntersectionObserver fade animations, and form logic.
- `/assets/`: Directory containing all visual assets (logos, hero backgrounds, and portfolio images).
- `README.md`: This file.

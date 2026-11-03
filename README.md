# IRP LMS — HTML & CSS Website

A responsive three-page recreation of the IRP LMS platform using only HTML5 and CSS3.

## Pages
- `index.html` — Home: hero banner and five-step learning journey
- `courses.html` — Courses: 9 embedded YouTube tutorials and explore banner
- `contact.html` — Contact Us: contact details panel and message form
- `style.css` — shared styles (colors defined as CSS variables in `:root`)

## Run locally
Open `index.html` in any browser. No build step or JavaScript required.

## Publish on GitHub
1. Create a **public** repository on GitHub.
2. Push these files:
   ```
   git init
   git add .
   git commit -m "IRP LMS website"
   git branch -M main
   git remote add origin https://github.com/<your-username>/<repo-name>.git
   git push -u origin main
   ```
3. Open the repo link in a private window to confirm it's public, then submit the URL.
   (Optional: enable GitHub Pages under Settings → Pages to host it live.)

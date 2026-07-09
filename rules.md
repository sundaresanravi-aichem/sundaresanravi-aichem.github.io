# Sundaresan Ravi | Academic Portfolio

This repository contains the source code for my academic portfolio website. It is built using HTML5, CSS3, and Vanilla JavaScript, optimized for performance and accessibility.

## 📂 Folder Structure

- `/` : Core HTML files for each page (e.g., `index.html`, `about.html`, `tools.html`).
- `/css` : Contains `style.css` which provides the unified styling and responsive design rules, including light and dark mode functionality.
- `/js` : Contains `main.js` which handles the dark mode toggle, mobile navigation menu, and active link highlighting.
- `/images` : Directory for storing profile pictures and project-related screenshots.
- `/documents` : Directory for storing downloadable files like `Sundaresan_Ravi_CV.pdf`.
- `/icons` : Directory for favicons and related web-app icons.
- `/data` : Directory for any structured JSON files if required for future dynamic elements.

## 🛠️ Technologies Used

- Semantic HTML5
- CSS3 (CSS Variables for themes, Flexbox, Grid)
- Vanilla JavaScript
- Google Fonts (Inter)
- FontAwesome (Icons)

## 🚀 Deployment to GitHub Pages

1. Initialize a Git repository in this folder if you haven't already:
   ```bash
   git init
   git add .
   git commit -m "Initial commit"
   ```
2. Create a new repository on GitHub named `sundaresanravi.github.io` (or your preferred repository name).
3. Push your code to the repository:
   ```bash
   git remote add origin https://github.com/yourusername/your-repo-name.git
   git branch -M main
   git push -u origin main
   ```
4. On GitHub, navigate to the repository **Settings** > **Pages**.
5. Select the `main` branch as the source and click **Save**.
6. Your website will be live in a few minutes!

## 🔍 Submitting to Google Search Console

1. Go to [Google Search Console](https://search.google.com/search-console).
2. Click **Add property** and select the **URL prefix** option.
3. Enter the full URL of your deployed website (e.g., `https://sundaresanravi.github.io`) and click Continue.
4. Choose an ownership verification method. If using GitHub Pages, the easiest method is the **HTML tag**. Copy the provided `<meta>` tag and paste it into the `<head>` of your `index.html` file, then commit and push the change.
5. Once verified, go to the **Sitemaps** section in the left sidebar.
6. Enter `sitemap.xml` in the input field and click **Submit**. Google will now crawl your site using the provided sitemap.

## 📝 Updating the Website

- **To update your CV**: Replace `documents/Sundaresan_Ravi_CV.pdf` with your latest PDF file, keeping the name exactly the same, or update the file link in `resume.html`.
- **To change the domain**: Update `https://yourdomain.com/` in `index.html` (metadata tags), `robots.txt`, and `sitemap.xml` to match your actual deployed URL.
- **To add new projects**: Open `projects.html` and copy one of the existing `<div class="card">...</div>` blocks, paste it, and modify the content.

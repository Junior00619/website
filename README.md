# Alan Pena - Portfolio Website

A modern, responsive portfolio website showcasing software engineering projects and experience in robotics, full-stack development, and distributed systems.

## 🎨 Design

- **Style**: Clean, minimalist dark theme inspired by leading developer portfolios
- **Typography**: JetBrains Mono (monospace) + Instrument Serif (display)
- **Colors**: Navy blue background with cyan/teal accents
- **Features**: Smooth scrolling, fade-in animations, mobile responsive, tab-based experience section

## 🚀 Quick Start

### Local Development

1. Clone this repository
2. Open `index.html` in your browser
3. That's it! No build process needed.

### Deploy to GitHub Pages (Free Hosting!)

1. **Create a GitHub repository**
   ```bash
   # In your portfolio folder
   git init
   git add .
   git commit -m "Initial portfolio commit"
   ```

2. **Push to GitHub**
   ```bash
   # Create a new repo on GitHub first, then:
   git remote add origin https://github.com/YOUR-USERNAME/YOUR-REPO-NAME.git
   git branch -M main
   git push -u origin main
   ```

3. **Enable GitHub Pages**
   - Go to your repository on GitHub
   - Click `Settings` → `Pages`
   - Under "Source", select `main` branch
   - Click `Save`
   - Your site will be live at: `https://YOUR-USERNAME.github.io/YOUR-REPO-NAME`

### Deploy to Custom Domain (Optional)

1. Buy a domain (Namecheap, Google Domains, etc.)
2. In your GitHub Pages settings, add your custom domain
3. Update your domain's DNS settings:
   - Add a CNAME record pointing to `YOUR-USERNAME.github.io`
4. Wait for DNS propagation (can take up to 24 hours)

## 📝 Customization Guide

### Adding Your Photo

Replace the placeholder in the "About" section:

```html
<!-- Find this in index.html around line 135 -->
<div class="image-placeholder">
    <!-- Replace the SVG with: -->
    <img src="path/to/your-photo.jpg" alt="Alan Pena">
</div>
```

### Adding Real Projects

1. **Featured Projects**: Update the project sections starting around line 315 in `index.html`
2. **Project Cards**: Add more cards in the "Other Projects" section around line 450

Example project card:
```html
<article class="project-card">
    <div class="project-card-header">
        <svg><!-- folder icon --></svg>
        <div class="project-card-links">
            <a href="YOUR_GITHUB_LINK"><!-- GitHub icon --></a>
            <a href="YOUR_LIVE_DEMO"><!-- External link icon --></a>
        </div>
    </div>
    <h4 class="project-card-title">Your Project Name</h4>
    <p class="project-card-description">
        Description of what your project does and the problems it solves.
    </p>
    <ul class="project-card-tech">
        <li>Tech 1</li>
        <li>Tech 2</li>
        <li>Tech 3</li>
    </ul>
</article>
```

### Adding Project Screenshots

Replace the placeholder SVGs with actual images:

```html
<!-- Find placeholder-image divs and replace SVG with: -->
<img src="path/to/screenshot.png" alt="Project screenshot">
```

**Pro tip**: For best results, use screenshots that are:
- 1200px x 800px (or similar 3:2 ratio)
- Compressed (use TinyPNG or similar)
- Named descriptively (e.g., `uav-dashboard.png`)

### Updating Your Info

All personal info is in `index.html`. Search for:
- Email: `alanpena91@gmail.com`
- GitHub: `Junior00619`
- LinkedIn: `alan-pena-030a95103`
- Phone: `2019825859`

### Changing Colors

Edit the CSS variables in `styles.css` (lines 1-13):

```css
:root {
    --navy: #0a192f;           /* Dark background */
    --green: #64ffda;          /* Accent color */
    /* etc... */
}
```

Popular alternative color schemes:
- **Purple**: `--green: #c792ea;`
- **Orange**: `--green: #f78c6c;`
- **Blue**: `--green: #82aaff;`

### Adding a Resume PDF

1. Add your resume PDF to the portfolio folder
2. Update the link in the "Contact" section:
```html
<a href="your-resume.pdf" class="btn btn-secondary" download>Download Resume</a>
```

## 📂 File Structure

```
portfolio/
├── index.html          # Main HTML file
├── styles.css          # All styling
├── script.js           # Interactive features
└── README.md          # This file
```

## 🎯 Features

- ✅ Fully responsive (mobile, tablet, desktop)
- ✅ Smooth scroll navigation
- ✅ Fade-in animations on scroll
- ✅ Tab-based experience section
- ✅ Mobile hamburger menu
- ✅ Project cards with hover effects
- ✅ Social links in footer
- ✅ Custom scrollbar
- ✅ SEO-friendly meta tags
- ✅ Fast loading (no dependencies!)
- 🎁 Easter egg (try the Konami code!)

## 🛠️ Built With

- Pure HTML5, CSS3, JavaScript
- Google Fonts (JetBrains Mono, Instrument Serif)
- No frameworks or libraries needed!

## 📱 Browser Support

- Chrome (recommended)
- Firefox
- Safari
- Edge
- Mobile browsers (iOS Safari, Chrome Mobile)

## 💡 Tips for Your Portfolio

1. **Add live demos**: Host your projects on GitHub Pages, Vercel, or Netlify
2. **Write good descriptions**: Focus on the *problem* you solved, not just the tech
3. **Use real screenshots**: Shows you actually built the thing
4. **Keep it updated**: Add new projects as you build them
5. **Get feedback**: Share with friends/mentors before applying to jobs
6. **Track analytics**: Add Google Analytics to see how many people visit

## 🚦 Next Steps

1. [ ] Add your photo
2. [ ] Replace placeholder projects with real ones
3. [ ] Add project screenshots
4. [ ] Update all personal links
5. [ ] Test on mobile
6. [ ] Deploy to GitHub Pages
7. [ ] Share with friends for feedback
8. [ ] Add to resume and LinkedIn

## 📧 Questions?

If you need help customizing anything, just ask!

---

**Good luck with your job search! 🚀**
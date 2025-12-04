# Srija Karicherla - Portfolio Website

A clean, modern, and professional portfolio website showcasing my experience as a Data Analyst, projects, skills, and achievements.

## Features

- 🎨 Modern and clean design
- 📱 Fully responsive (mobile, tablet, desktop)
- ⚡ Smooth scrolling navigation
- 🎯 Interactive animations
- 🚀 Optimized for performance
- 📄 All sections from resume included

## Technologies Used

- HTML5
- CSS3 (with CSS Variables)
- Vanilla JavaScript
- Google Fonts (Inter)

## Sections

1. **Hero Section** - Introduction with contact information
2. **About** - Professional summary
3. **Skills** - Technical skills organized by category
4. **Experience** - Professional work experience with timeline
5. **Projects** - Featured projects with descriptions
6. **Education** - Academic qualifications
7. **Certifications** - Professional certifications
8. **Contact** - Contact information and links

## Deployment to GitHub Pages

### Step 1: Create a GitHub Repository

1. Go to [GitHub](https://github.com) and sign in
2. Click the "+" icon in the top right corner
3. Select "New repository"
4. Name it `portfolio` (or your preferred name)
5. Make it **Public** (required for free GitHub Pages)
6. **Do NOT** initialize with README, .gitignore, or license
7. Click "Create repository"

### Step 2: Initialize Git and Push Files

Open your terminal/command prompt in the portfolio directory and run:

```bash
# Initialize git repository
git init

# Add all files
git add .

# Commit files
git commit -m "Initial commit: Portfolio website"

# Add your GitHub repository as remote (replace YOUR_USERNAME with your GitHub username)
git remote add origin https://github.com/YOUR_USERNAME/portfolio.git

# Push to GitHub
git branch -M main
git push -u origin main
```

### Step 3: Enable GitHub Pages

1. Go to your repository on GitHub
2. Click on **Settings** tab
3. Scroll down to **Pages** section in the left sidebar
4. Under **Source**, select:
   - Branch: `main`
   - Folder: `/ (root)`
5. Click **Save**
6. Wait a few minutes for GitHub to build your site
7. Your site will be available at: `https://YOUR_USERNAME.github.io/portfolio/`

### Step 4: Custom Domain (Optional)

If you have a custom domain:
1. In the Pages settings, add your custom domain
2. Update your domain's DNS settings as instructed by GitHub
3. Wait for DNS propagation (can take up to 24 hours)

## Local Development

To view the website locally:

1. Simply open `index.html` in your web browser
2. Or use a local server:

```bash
# Using Python 3
python -m http.server 8000

# Using Node.js (if you have http-server installed)
npx http-server

# Using PHP
php -S localhost:8000
```

Then open `http://localhost:8000` in your browser.

## Customization

### Update Contact Information

Edit the contact links in `index.html`:
- Update the LinkedIn URL in the hero section
- Update email and phone number if needed

### Change Colors

Edit CSS variables in `styles.css`:
```css
:root {
    --primary-color: #2563eb;  /* Change this */
    --primary-dark: #1e40af;   /* Change this */
    /* ... other variables */
}
```

### Add/Remove Sections

Simply add or remove sections in `index.html` and update the navigation menu accordingly.

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## License

This portfolio is open source and available for personal use.

## Contact

- **Email:** karicherlasrija@gmail.com
- **Phone:** +1 (737) 707-8937
- **LinkedIn:** [Your LinkedIn Profile]

---

Made with ❤️ by Srija Karicherla


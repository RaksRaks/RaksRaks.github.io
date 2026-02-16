# Maloko Rakumako - Portfolio Website

Professional portfolio website showcasing my Data Science and Machine Learning projects.

## Live Demo

Visit: [https://raksraks.github.io/portfolio](https://raksraks.github.io/portfolio)

## Features

- Responsive design that works on all devices
- Modern and clean UI
- Smooth scrolling and animations
- Project showcase with GitHub links
- Skills and experience sections
- Contact information

## Technologies Used

- HTML5
- CSS3 (with CSS Grid and Flexbox)
- JavaScript (Vanilla)
- Font Awesome Icons

## Setup Instructions

### 1. Add Your Profile Picture

Replace `images/profile.jpg` with your professional photo.

### 2. Add Project Images (Optional)

Add images for your projects in the `images/` folder:
- `electricity-forecasting.jpg`
- `predictive-maintenance.jpg`
- `fault-detection.jpg`

Or use placeholder images from [Unsplash](https://unsplash.com/) or [Pexels](https://www.pexels.com/).

### 3. Update Links

Update the following in `index.html`:
- LinkedIn URL (line 67)
- GitHub URLs (already set to your repos)
- Portfolio website link if you have a custom domain

## Deployment to GitHub Pages

### Method 1: Using GitHub Web Interface

1. Create a new repository named `portfolio` or `your-username.github.io`
2. Upload all files from this folder
3. Go to Settings > Pages
4. Select "main" branch as source
5. Click Save
6. Your site will be live at `https://your-username.github.io/portfolio`

### Method 2: Using Git Command Line

```bash
# Navigate to the portfolio-website folder
cd "My Projects/Active_Projects/portfolio-website"

# Initialize git repository
git init

# Add all files
git add .

# Commit
git commit -m "Initial commit: Portfolio website"

# Create repository on GitHub (via web or CLI)
gh repo create portfolio --public --source=. --remote=origin --push

# Or if repository already exists
git remote add origin https://github.com/RaksRaks/portfolio.git
git branch -M main
git push -u origin main

# Enable GitHub Pages
gh repo edit --enable-pages --pages-branch main
```

### Method 3: Using GitHub Desktop

1. Open GitHub Desktop
2. File > Add Local Repository
3. Select the portfolio-website folder
4. Publish repository to GitHub
5. Enable GitHub Pages in repository settings

## Customization

### Colors

Edit CSS variables in `css/style.css`:

```css
:root {
    --primary-color: #2563eb;  /* Change to your preferred color */
    --secondary-color: #1e40af;
    --accent-color: #3b82f6;
}
```

### Content

Update content in `index.html`:
- Hero section text
- About me description
- Project descriptions
- Skills list
- Work experience
- Contact information

### Adding More Projects

Copy a project card in the projects section and update:
- Project title
- Description
- Tags
- GitHub link
- Image

## File Structure

```
portfolio-website/
├── index.html          # Main HTML file
├── css/
│   └── style.css      # Styles
├── js/
│   └── script.js      # JavaScript functionality
├── images/
│   ├── profile.jpg    # Your profile picture
│   ├── electricity-forecasting.jpg
│   ├── predictive-maintenance.jpg
│   └── fault-detection.jpg
└── README.md          # This file
```

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## Performance

- Lightweight (< 100KB without images)
- Fast loading
- Optimized for mobile
- SEO friendly

## License

MIT License - Feel free to use this template for your own portfolio

## Contact

Maloko Gerald Rakumako
- Email: mraksunator@gmail.com
- GitHub: [@RaksRaks](https://github.com/RaksRaks)
- Phone: +27 66 011 6417

---

Built with passion for Data Science and Machine Learning

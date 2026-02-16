# Portfolio Setup Guide

## Step 1: Add Your Profile Picture

1. Save your professional photo as `profile.jpg`
2. Place it in the `images/` folder
3. Recommended size: 800x800px or larger (square format works best)

## Step 2: Update Content

Open `index.html` and update:
- LinkedIn URL (search for "linkedin.com/in/maloko-rakumako")
- Add path to your CV PDF (search for "path/to/your/cv.pdf")

## Step 3: Deploy to GitHub Pages

### Quick Deploy:

```bash
# Navigate to portfolio folder
cd "My Projects/Active_Projects/portfolio-website"

# Initialize git
git init

# Add all files
git add .

# Commit
git commit -m "Initial commit: Dark theme portfolio"

# Create GitHub repository and push
gh repo create portfolio --public --source=. --remote=origin --push

# Your site will be live at: https://raksraks.github.io/portfolio
```

### Enable GitHub Pages:

1. Go to your repository on GitHub
2. Click Settings > Pages
3. Under "Source", select "main" branch
4. Click Save
5. Your site will be live in a few minutes!

## Step 4: Test Locally (Optional)

You can test the site locally by opening `index.html` in your browser, or use a simple HTTP server:

```bash
# Using Python
python -m http.server 8000

# Then visit: http://localhost:8000
```

## Customization Tips

### Change Colors:

Edit `css/style.css` and modify the CSS variables:

```css
:root {
    --primary-color: #14b8a6;  /* Teal - change to your preferred color */
    --secondary-color: #0d9488;
    --accent-color: #2dd4bf;
}
```

### Add Project Images:

1. Add images to the `images/` folder
2. Update image paths in `index.html`
3. Recommended size: 1200x600px

### Update Projects:

In `index.html`, find the projects section and update:
- Project titles
- Descriptions
- GitHub links
- Tags/technologies

## Troubleshooting

### Images not showing?
- Make sure images are in the `images/` folder
- Check file names match exactly (case-sensitive)
- Use relative paths: `images/profile.jpg`

### Site not updating on GitHub Pages?
- Wait 2-3 minutes for changes to deploy
- Clear your browser cache (Ctrl+Shift+R or Cmd+Shift+R)
- Check GitHub Actions tab for build status

### Mobile menu not working?
- Make sure `js/script.js` is loaded
- Check browser console for errors (F12)

## Your Portfolio URL

Once deployed, your portfolio will be available at:
**https://raksraks.github.io/portfolio**

Share this link on:
- Your CV
- LinkedIn profile
- Email signature
- GitHub profile README

## Need Help?

- Check the browser console (F12) for errors
- Validate HTML: https://validator.w3.org/
- Test responsiveness: Use browser dev tools (F12 > Toggle device toolbar)

---

Good luck with your job search! 🚀

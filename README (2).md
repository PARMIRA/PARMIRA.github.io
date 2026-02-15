# Mira Parikh - Portfolio Website

A clean, professional portfolio website showcasing my projects, experience, and skills.

## 🚀 Deployment Instructions for GitHub Pages

### Step 1: Create GitHub Repository

1. Go to [GitHub](https://github.com) and sign in
2. Click the "+" icon in the top right corner
3. Select "New repository"
4. Name it **exactly**: `PARMIRA.github.io` (replace PARMIRA with your GitHub username)
5. Make it **Public**
6. **DO NOT** initialize with README, .gitignore, or license
7. Click "Create repository"

### Step 2: Upload Files to GitHub

**Option A: Using GitHub Website (Easiest)**

1. On your new repository page, click "uploading an existing file"
2. Drag and drop these three files:
   - `index.html`
   - `style.css`
   - `script.js`
3. Scroll down and click "Commit changes"
4. Wait 1-2 minutes
5. Visit `https://PARMIRA.github.io` (replace PARMIRA with your username)

**Option B: Using Git Command Line**

```bash
# Navigate to the folder containing your portfolio files
cd /path/to/portfolio

# Initialize git repository
git init

# Add all files
git add .

# Commit files
git commit -m "Initial portfolio commit"

# Add your GitHub repository as remote
git remote add origin https://github.com/PARMIRA/PARMIRA.github.io.git

# Push to GitHub
git branch -M main
git push -u origin main
```

### Step 3: Enable GitHub Pages (if not automatic)

1. Go to your repository on GitHub
2. Click "Settings"
3. Scroll down to "Pages" in the left sidebar
4. Under "Source", select "main" branch
5. Click "Save"
6. Wait 1-2 minutes for deployment

Your site will be live at: `https://PARMIRA.github.io`

## 📝 Customization

### Update Your Information

1. **Personal Info**: Edit `index.html` lines with your email, LinkedIn, GitHub links
2. **Projects**: Update the project cards in the "projects" section with your actual GitHub repo links
3. **Experience**: Modify dates and descriptions as needed
4. **Colors**: Change colors in `style.css` under `:root` variables

### Adding New Projects

Copy this template in `index.html` under the projects section:

```html
<div class="project-card">
    <h3>Project Name</h3>
    <p class="tech-stack">Tech Stack Here</p>
    <p>Project description here...</p>
    <div class="project-links">
        <a href="your-github-link" class="project-link">View Code →</a>
    </div>
</div>
```

## 🎨 Color Customization

Edit these variables in `style.css`:

```css
:root {
    --primary-color: #2563eb;      /* Main blue color */
    --secondary-color: #1e40af;    /* Darker blue */
    --text-color: #1f2937;         /* Main text */
    --text-light: #6b7280;         /* Secondary text */
}
```

## 📱 Features

- ✅ Fully responsive (mobile, tablet, desktop)
- ✅ Smooth scrolling navigation
- ✅ Animated project cards
- ✅ Clean, professional design
- ✅ SEO-friendly
- ✅ Fast loading

## 🔧 Troubleshooting

**Site not loading?**
- Wait 2-3 minutes after pushing to GitHub
- Check that repository name is exactly `yourusername.github.io`
- Ensure repository is Public
- Check Settings > Pages to confirm deployment

**Want to use a custom domain?**
- Buy a domain (e.g., from Namecheap, Google Domains)
- In repository Settings > Pages, add your custom domain
- Update DNS records at your domain provider

## 📞 Questions?

Feel free to reach out if you need help deploying!

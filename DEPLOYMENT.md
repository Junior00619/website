# 🚀 GitHub Pages Deployment Guide

## Step-by-Step Instructions

### 1. Prepare Your Files
Make sure you have all these files in one folder:
- index.html
- styles.css
- script.js
- README.md

### 2. Create a GitHub Repository

**Option A: Via GitHub Website**
1. Go to https://github.com
2. Click the `+` in top right → `New repository`
3. Name it: `portfolio` (or any name you want)
4. Make it **Public**
5. Click `Create repository`

**Option B: Via Command Line**
```bash
# Navigate to your portfolio folder
cd path/to/portfolio

# Initialize git
git init

# Add all files
git add .

# Commit
git commit -m "Initial portfolio commit"

# Create repo on GitHub first, then link it
git remote add origin https://github.com/YOUR-USERNAME/portfolio.git

# Push to GitHub
git branch -M main
git push -u origin main
```

### 3. Enable GitHub Pages

1. Go to your repository on GitHub
2. Click `Settings` (top menu)
3. Click `Pages` (left sidebar)
4. Under "Branch":
   - Select `main`
   - Keep folder as `/ (root)`
   - Click `Save`

### 4. Wait & View

- GitHub will build your site (takes 1-2 minutes)
- Your site will be live at: `https://YOUR-USERNAME.github.io/portfolio`
- You'll see a green checkmark when it's ready

### 5. Update Your Links

Don't forget to update:
- Your resume (add the portfolio URL)
- LinkedIn (add to websites section)
- Email signature
- GitHub profile README

---

## 🎯 Pro Tips

### Use a Custom URL

Want `YOUR-USERNAME.github.io` instead of `/portfolio`?

1. Rename your repository to: `YOUR-USERNAME.github.io`
2. Your site will automatically be at: `https://YOUR-USERNAME.github.io`

### Custom Domain (Optional)

1. Buy a domain (e.g., `alanpena.dev`)
2. In GitHub Pages settings, add your domain
3. Update DNS records:
   ```
   Type: CNAME
   Host: www
   Value: YOUR-USERNAME.github.io
   ```
4. Wait 24 hours for DNS propagation

### Making Updates

After making changes to your portfolio:

```bash
git add .
git commit -m "Updated projects section"
git push
```

Your site updates automatically in 1-2 minutes!

---

## ❓ Troubleshooting

**Site not loading?**
- Wait 2-3 minutes after enabling GitHub Pages
- Check that `index.html` is in the root folder
- Make sure repository is Public

**CSS not loading?**
- Check file names match exactly (case-sensitive)
- Make sure `styles.css` is in the same folder as `index.html`

**404 Error?**
- Verify the URL is correct: `https://YOUR-USERNAME.github.io/REPO-NAME`
- Check GitHub Pages settings are correct

**Need to undo changes?**
```bash
git reset --hard HEAD~1  # Go back one commit
git push -f              # Force push (careful!)
```

---

## 📞 Need Help?

Common issues:
1. **Wrong URL**: Double-check your username and repo name
2. **Files in subfolder**: Move files to root folder
3. **Private repo**: Must be Public for free GitHub Pages
4. **Case sensitivity**: `Index.html` ≠ `index.html`

Still stuck? Check GitHub's official guide:
https://docs.github.com/en/pages

---

Good luck! 🎉
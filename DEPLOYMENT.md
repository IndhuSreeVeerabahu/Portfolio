# How to Deploy Your Portfolio Publicly

## Option 1: GitHub Pages (Recommended - Free & Easy)

### Step 1: Create a GitHub Account
- Go to https://github.com and sign up (if you don't have an account)

### Step 2: Create a New Repository
1. Click the "+" icon in the top right → "New repository"
2. Repository name: `portfolio` or `my-portfolio` (or any name you like)
3. Make it **Public**
4. **DO NOT** initialize with README, .gitignore, or license
5. Click "Create repository"

### Step 3: Upload Your Files
1. Open your Portfolio folder in File Explorer
2. Right-click → "Open in Terminal" or "Git Bash Here"
3. Run these commands:

```bash
git init
git add .
git commit -m "Initial commit - Portfolio website"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git
git push -u origin main
```

Replace `YOUR_USERNAME` and `YOUR_REPO_NAME` with your actual GitHub username and repository name.

### Step 4: Enable GitHub Pages
1. Go to your repository on GitHub
2. Click "Settings" tab
3. Scroll down to "Pages" in the left sidebar
4. Under "Source", select "Deploy from a branch"
5. Select branch: `main` and folder: `/ (root)`
6. Click "Save"
7. Wait 1-2 minutes, then your site will be live at:
   `https://YOUR_USERNAME.github.io/YOUR_REPO_NAME/`

---

## Option 2: Netlify (Easiest - Drag & Drop)

### Step 1: Go to Netlify
- Visit https://www.netlify.com
- Sign up for free (can use GitHub account)

### Step 2: Deploy
1. Drag and drop your entire Portfolio folder onto the Netlify dashboard
2. Your site will be live in seconds!
3. You'll get a URL like: `https://random-name-123.netlify.app`
4. You can change the site name in Site settings → Change site name

---

## Option 3: Vercel (Also Very Easy)

### Step 1: Go to Vercel
- Visit https://vercel.com
- Sign up for free (can use GitHub account)

### Step 2: Deploy
1. Click "Add New Project"
2. Import your GitHub repository (if you pushed to GitHub)
   OR
   Drag and drop your Portfolio folder
3. Click "Deploy"
4. Your site will be live at: `https://your-project.vercel.app`

---

## Option 4: Railway (You mentioned this in your skills!)

### Step 1: Go to Railway
- Visit https://railway.app
- Sign up for free

### Step 2: Deploy
1. Click "New Project"
2. Select "Deploy from GitHub repo" (if you have it on GitHub)
   OR
   Select "Empty Project" and upload files
3. Configure as a static site
4. Your site will be live!

---

## Important Notes:

1. **Make sure your assets folder has the files:**
   - `assets/profile.jpg` - Your profile photo
   - `assets/resume.pdf` - Your resume

2. **Test your live site:**
   - Check all links work
   - Test the resume download
   - Test on mobile devices
   - Test dark mode toggle

3. **Custom Domain (Optional):**
   - All platforms allow you to add a custom domain (e.g., `yourname.com`)
   - Usually free or very cheap

4. **Update Links:**
   - Once deployed, update your LinkedIn, resume, etc. with your portfolio URL

---

## Quick Start (Fastest Method):

1. **GitHub Pages** - Best for long-term, free hosting
2. **Netlify** - Fastest deployment (drag & drop)
3. **Vercel** - Great performance, easy setup

All three are completely free and perfect for portfolio websites!


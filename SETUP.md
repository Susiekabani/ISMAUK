# GitHub Pages Setup Guide

## Step-by-Step Instructions for Deploying ISMAUK Awards to GitHub Pages

### Prerequisites
- GitHub account (free at github.com)
- This repository code

---

## Method 1: Using GitHub Web Interface (Easiest)

### Step 1: Create a GitHub Repository

1. Go to **github.com** and log in
2. Click **+** (top right) → **New repository**
3. Name it: `ismauk-awards-2026`
4. Add description: "Online application portal for ISMAUK Stress Management Awards 2026"
5. Choose **Public** (so it's accessible to applicants)
6. Check ☑️ **Add a README file**
7. Click **Create repository**

### Step 2: Upload Files

1. In your new repository, click **Add file** → **Upload files**
2. Drag and drop these files:
   - `index.html`
   - `README.md`
   - `.gitignore`
   - `_config.yml`
3. Scroll down and click **Commit changes**

### Step 3: Enable GitHub Pages

1. Go to **Settings** (top right of repo)
2. Scroll down to **Pages** section
3. Under **Source**, select **Deploy from a branch**
4. Select **main** branch
5. Click **Save**
6. Wait 1-2 minutes for build to complete
7. You'll see: "Your site is published at: `https://yourusername.github.io/ismauk-awards-2026`"

### Step 4: Share Your Link

Your application form is now live! Share the link with applicants.

---

## Method 2: Using Git Command Line

### Step 1: Create Repository on GitHub
(Follow Steps 1-2 above)

### Step 2: Clone and Add Files

```bash
git clone https://github.com/yourusername/ismauk-awards-2026.git
cd ismauk-awards-2026
```

### Step 3: Copy Your Files

Copy these files into the directory:
- `index.html`
- `README.md`
- `.gitignore`
- `_config.yml`

### Step 4: Commit and Push

```bash
git add .
git commit -m "Initial commit: ISMAUK Awards application form"
git push origin main
```

### Step 5: Enable GitHub Pages
(Follow Step 3 above)

---

## Method 3: Using GitHub Desktop (Visual)

1. Download GitHub Desktop from desktop.github.com
2. Sign in with your GitHub account
3. Click **File** → **Clone Repository**
4. Select `ismauk-awards-2026`
5. Click **Clone**
6. Copy the files into the folder
7. In GitHub Desktop:
   - Write summary: "Add ISMAUK Awards application form"
   - Click **Commit to main**
   - Click **Push origin**
8. Enable GitHub Pages (Step 3 above)

---

## After Deployment

### Share Your Link
```
https://yourusername.github.io/ismauk-awards-2026
```

### Customize the Site

Edit `index.html` directly in GitHub:
1. Open `index.html` in your repository
2. Click the ✏️ (edit) icon
3. Make changes:
   - Change email address: search for `admin@isma.org.uk`
   - Update colors: edit CSS variables at top
   - Modify award criteria: edit the relevant sections
4. Scroll down and click **Commit changes**
5. Changes go live automatically in 1-2 minutes

### Monitor Applications

Applicants will:
1. Fill in the form on your site
2. Download their PDF
3. Email it to the address in the form

Keep checking that email address for submissions!

---

## Troubleshooting

### Site Not Showing?
- Wait 2-3 minutes after enabling Pages
- Check that branch is set to `main` in Settings → Pages
- Ensure `index.html` is in the root directory

### Want to Use a Custom Domain?
1. Go to **Settings** → **Pages**
2. Under **Custom domain**, enter your domain (e.g., `awards.ismauk.org.uk`)
3. Update DNS records with your domain provider
4. GitHub will show instructions for your provider

### Need to Make Changes?
- Edit files directly in GitHub by clicking the ✏️ icon
- Or use Git command line if you prefer
- Changes deploy automatically

---

## Security Notes

✅ **Safe:** This form stores NO data on any server
✅ **Private:** All data stays in user's browser until they download PDF
✅ **Secure:** HTTPS automatically enabled by GitHub Pages
✅ **Compliant:** No personal data collected or stored

---

## Support

For setup help:
- GitHub Pages docs: pages.github.com
- GitHub Help: help.github.com
- ISMAUK: admin@ismauk.org.uk

---

**That's it! Your application portal is live! 🎉**

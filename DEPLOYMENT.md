# Deployment Guide

Complete instructions for deploying the ISMAUK Awards portal to GitHub.

## Method 1: GitHub Web Interface (Recommended)

### Step 1: Create a New Repository

1. Go to **github.com** and log in
2. Click the **+** icon (top right) → **New repository**
3. Fill in:
   - **Repository name:** `ismauk-awards-2026`
   - **Description:** ISMAUK Stress Management Awards 2026 Application Portal
   - **Visibility:** Public
   - Check ☑️ **Add a README file**
4. Click **Create repository**

### Step 2: Upload Files

1. In your new repository, click **Add file** → **Upload files**
2. Select or drag and drop these files:
   - `index.html`
   - `README.md`
   - `QUICKSTART.md`
   - `.gitignore`
   - `LICENSE`
   - `_config.yml`
3. Click **Commit changes**

### Step 3: Enable GitHub Pages

1. Click **Settings** (top right of repository)
2. Scroll down to **Pages** section
3. Under **Source**, select **Deploy from a branch**
4. Select **main** branch
5. Click **Save**
6. Wait 1-2 minutes for the site to build
7. You'll see: "Your site is published at: `https://yourusername.github.io/ismauk-awards-2026`"

### Step 4: Test and Share

1. Visit your URL: `https://yourusername.github.io/ismauk-awards-2026`
2. Test the form (select options, fill fields, download PDF)
3. Share the link with applicants

---

## Method 2: Git Command Line

### Prerequisites
- Git installed on your computer
- GitHub account

### Steps

**1. Create repository on GitHub**
(Follow Steps 1-2 from Method 1)

**2. Clone to your computer**
```bash
git clone https://github.com/yourusername/ismauk-awards-2026.git
cd ismauk-awards-2026
```

**3. Add the files**
Copy these files into the directory:
- index.html
- README.md
- QUICKSTART.md
- .gitignore
- LICENSE
- _config.yml

**4. Commit and push**
```bash
git add .
git commit -m "Initial commit: ISMAUK Awards 2026 application portal"
git push origin main
```

**5. Enable GitHub Pages**
(Follow Step 3 from Method 1)

---

## Method 3: GitHub Desktop

### Prerequisites
- GitHub Desktop installed (desktop.github.com)
- GitHub account

### Steps

**1. Create repository on GitHub**
(Follow Steps 1-2 from Method 1)

**2. Clone with GitHub Desktop**
- Open GitHub Desktop
- Click **File** → **Clone Repository**
- Select `ismauk-awards-2026`
- Choose where to save it
- Click **Clone**

**3. Add files**
- Copy the 6 files into the folder
- GitHub Desktop will detect them

**4. Commit and push**
- In GitHub Desktop, write summary: "Add ISMAUK Awards application portal"
- Click **Commit to main**
- Click **Push origin**

**5. Enable GitHub Pages**
(Follow Step 3 from Method 1)

---

## After Deployment

### Share Your Portal

Your application portal is live at:
```
https://yourusername.github.io/ismauk-awards-2026
```

Share this link via:
- Email
- Website
- Social media
- LinkedIn
- Internal communications

### Monitor Submissions

1. Applicants will fill the form on your portal
2. They'll download a PDF
3. They'll email the PDF to the email address in your form
4. Check your email for submissions

### Make Updates

To edit the portal:

**Web Interface (Easiest):**
1. Open `index.html` in your repository
2. Click the ✏️ (edit) icon
3. Make your changes
4. Scroll down and click **Commit changes**
5. Changes go live automatically in 1-2 minutes

**Command Line:**
```bash
cd ismauk-awards-2026
# Edit index.html
git add index.html
git commit -m "Update: [describe change]"
git push origin main
```

---

## Customization Before or After Deployment

### Change Email Address

Find: `admin@ismauk.org.uk`
Replace with: your email address

This email is where applicants will email their PDFs.

### Change Deadline

Find: `30 September 2026`
Replace with: your application deadline date

### Change Colors

In `index.html`, locate the CSS variables (near the top in the `<style>` section):

```css
:root {
    --primary: #003d7a;        /* Navy blue */
    --accent: #a91e6a;         /* Magenta */
    /* ...other variables... */
}
```

Change these hex codes to your preferred colors.

### Update Award Criteria

Find the award tier descriptions and modify the text directly in `index.html`.

---

## Troubleshooting

### Site Not Showing?
- ✓ Wait 2-3 minutes after enabling Pages
- ✓ Check that branch is set to `main` in Settings → Pages
- ✓ Ensure `index.html` is in the root directory (not in a subfolder)
- ✓ Try refreshing the browser (Ctrl+F5 or Cmd+Shift+R)

### "404 Not Found" Error?
- ✓ Check the URL is correct: `https://yourusername.github.io/ismauk-awards-2026`
- ✓ Pages are still building (wait another minute)
- ✓ Check Settings → Pages → Source is set to `main` branch

### Changes Not Showing?
- ✓ Hard refresh your browser (Ctrl+F5 or Cmd+Shift+R)
- ✓ Clear browser cache
- ✓ Wait 1-2 minutes for GitHub Pages to rebuild
- ✓ Check that you committed and pushed your changes

### Using a Custom Domain?

1. Go to **Settings** → **Pages**
2. Under **Custom domain**, enter your domain (e.g., `awards.example.com`)
3. Click **Save**
4. Update your domain's DNS records:
   - GitHub will show you the exact DNS settings to use
   - This usually takes 5-30 minutes to take effect
5. Once DNS is updated, HTTPS will be automatically enabled

---

## Important Notes

✅ **No Backend Required** - This is a completely static site  
✅ **Data Privacy** - No data is stored on any server  
✅ **HTTPS Automatic** - GitHub Pages provides free HTTPS  
✅ **No Limits** - You can host unlimited sites on GitHub Pages  
✅ **Version Control** - Every change is tracked and reversible  

---

## Support

- **GitHub Pages Help:** https://pages.github.com
- **GitHub Documentation:** https://docs.github.com
- **Awards Support:** admin@ismauk.org.uk

---

**Your portal is now live!** 🎉

# Quick Start Guide

## Deploy in 5 Steps

### 1. Create Repository
- Go to **github.com** → Click **+** → **New repository**
- Name: `ismauk-awards-2026`
- Description: "ISMAUK Stress Management Awards 2026 Application Portal"
- Choose **Public**
- Click **Create repository**

### 2. Upload Files
- Click **Add file** → **Upload files**
- Drag and drop or select:
  - `index.html`
  - `README.md`
  - `.gitignore`
  - `LICENSE`
  - `QUICKSTART.md`

### 3. Enable GitHub Pages
- Go to **Settings** (top right)
- Scroll to **Pages** section
- **Source:** Select `main` branch
- Click **Save**
- Wait 1-2 minutes

### 4. Share the Link
Your portal is live at:
```
https://yourusername.github.io/ismauk-awards-2026
```

### 5. Monitor Submissions
- Applicants download PDFs from the form
- They email PDFs to: `admin@ismauk.org.uk`
- Check your email for submissions

---

## Customizing the Portal

### Change Email Address
In `index.html`, find and replace:
```
admin@ismauk.org.uk  →  youremail@example.com
```

### Change Application Deadline
Find and replace:
```
30 September 2026  →  Your Deadline Date
```

### Change Brand Colors
In `index.html`, find the CSS variables section:
```css
--primary: #003d7a        /* Navy blue */
--accent: #a91e6a         /* Magenta */
```

### Change Organization Name
Find and replace:
```
ISMAUK  →  Your Organization Name
```

---

## Features at a Glance

✅ 4-step application form  
✅ 3 award tiers (Bronze/Silver/Gold)  
✅ Dynamic question loading  
✅ PDF generation  
✅ Mobile responsive  
✅ No backend needed  
✅ Completely private  

---

## Files Explained

| File | Purpose |
|------|---------|
| `index.html` | Main application (everything in one file) |
| `README.md` | Full documentation |
| `QUICKSTART.md` | This quick reference |
| `.gitignore` | What Git should ignore |
| `LICENSE` | MIT License |

---

## Troubleshooting

### Site Not Showing?
- Wait 2-3 minutes after enabling Pages
- Check that branch is set to `main` in Settings → Pages
- Ensure `index.html` is in the root directory

### Want to Use a Custom Domain?
1. Go to **Settings** → **Pages**
2. Under **Custom domain**, enter your domain
3. Update DNS records with your domain provider
4. GitHub will show instructions

### Need to Make Changes?
1. Edit `index.html` directly in GitHub (click the ✏️ icon)
2. Changes deploy automatically in 1-2 minutes

---

## Key Info

- **Email submissions go to:** admin@ismauk.org.uk (or your custom email)
- **Data storage:** None - all info stays in user's browser
- **Security:** HTTPS automatically enabled
- **Cost:** Completely free with GitHub Pages

---

## Support

- GitHub Pages help: https://pages.github.com
- Questions: admin@ismauk.org.uk
- Issues: Open an issue on GitHub

---

**You're all set! Share your portal link with applicants!** 🎉

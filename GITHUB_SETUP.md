# GitHub Setup Guide - ISMAUK Sponsorship 2026

## Step-by-Step: Create a GitHub Repository and Push Files

### Prerequisites
- GitHub account (free: https://github.com/signup)
- Git installed on your computer (https://git-scm.com/download)
- Terminal/Command prompt access

---

## Option A: Create via GitHub Web Interface (Easiest)

### 1. Create New Repository on GitHub

1. Log in to GitHub (https://github.com)
2. Click **"+"** icon (top right) → **"New repository"**
3. Fill in details:
   - **Repository name**: `ismauk-sponsorship-2026` (or similar)
   - **Description**: "Professional sponsorship packages and marketing materials for ISMAUK 2026"
   - **Visibility**: Public (so anyone can view) or Private (only invited)
   - ✓ Check "Add a README file"
4. Click **"Create repository"**

### 2. Upload Files via Web Interface

1. In your new repository, click **"Add file"** → **"Upload files"**
2. Drag and drop these files:
   - `README.md` (already created above)
   - `index.html`
   - `sponsorship-packages.html`
   - `ISMAUK_Sponsorship_SHORT_ENHANCED.docx`
   - `ISMAUK_Sponsorship_LONG_ENHANCED.docx`
3. Add commit message: "Initial commit: Add sponsorship materials"
4. Click **"Commit changes"**

### 3. Verify & Setup Pages (Optional)

To make the HTML pages live:
1. Go to **Settings** → **Pages**
2. Under "Build and deployment":
   - Source: Select "Deploy from a branch"
   - Branch: Select "main", folder "/root"
3. Click **"Save"**

Your pages will be live at: `https://yourusername.github.io/ismauk-sponsorship-2026/`

---

## Option B: Clone & Push via Command Line (More Control)

### 1. Create Repository on GitHub
Follow steps 1-2 from Option A above.

### 2. Clone to Your Computer

Open Terminal/Command Prompt and run:

```bash
git clone https://github.com/yourusername/ismauk-sponsorship-2026.git
cd ismauk-sponsorship-2026
```

Replace `yourusername` with your GitHub username.

### 3. Add Your Files

Copy these files into the folder you just created:
- `index.html`
- `sponsorship-packages.html`
- `ISMAUK_Sponsorship_SHORT_ENHANCED.docx`
- `ISMAUK_Sponsorship_LONG_ENHANCED.docx`
- `README.md`

### 4. Commit & Push

```bash
# Stage all files
git add .

# Commit with message
git commit -m "Add sponsorship materials for 2026"

# Push to GitHub
git push origin main
```

Done! Your files are now on GitHub.

---

## Recommended Repository Structure

Organize your repository like this:

```
ismauk-sponsorship-2026/
├── README.md                                    # Main documentation
├── index.html                                   # Landing page
├── sponsorship-packages.html                    # Detailed page
├── docs/                                        # Word documents
│   ├── ISMAUK_Sponsorship_SHORT_ENHANCED.docx
│   └── ISMAUK_Sponsorship_LONG_ENHANCED.docx
├── .gitignore                                   # (Optional) Ignore file list
└── CHANGELOG.md                                 # (Optional) Version history
```

### Create folders via command line:

```bash
mkdir docs
mv *.docx docs/
git add .
git commit -m "Organize files into docs folder"
git push origin main
```

---

## Useful GitHub Features

### Enable Issues (for feedback)
**Settings** → **Features** → Check "Issues"

### Add Description & Links
1. Go to repository homepage
2. Click **Edit** (pencil icon next to repo name)
3. Add description and website link:
   - Description: "ISMAUK sponsorship packages 2026"
   - Website: https://isma.org.uk

### Create Releases (for versions)
1. Click **Releases** (right sidebar)
2. Click **Create a new release**
3. Set:
   - Tag: `v1.0` 
   - Title: "ISMAUK Sponsorship 2026 - Version 1.0"
   - Description: List what's included
4. Publish

---

## Making Changes Later

### Via Web Interface:
1. Open file → Click pencil icon
2. Make edits → "Commit changes"

### Via Command Line:
```bash
# Make changes to files locally
# Then:
git add .
git commit -m "Update [description of changes]"
git push origin main
```

---

## Sharing Your Repository

### Direct Links:
- **Repository**: https://github.com/yourusername/ismauk-sponsorship-2026
- **Landing page**: https://yourusername.github.io/ismauk-sponsorship-2026/index.html
- **Detailed page**: https://yourusername.github.io/ismauk-sponsorship-2026/sponsorship-packages.html
- **Download files**: Click **Code** → **Download ZIP**

### Embed in Email:
```
View our 2026 sponsorship packages:
https://github.com/yourusername/ismauk-sponsorship-2026
```

### Share on LinkedIn:
```
🎯 Exciting news! ISMAUK sponsorship packages for 2026 are now available.

Five ways to partner with us:
✓ Sponsor the Year (£7,500)
✓ Sponsor the Week (£6,000)
✓ Sponsor the Summit (£4,500)
✓ Sponsor the Awards (£2,500)
✓ Sponsor a Session (£750)

View details: https://github.com/yourusername/ismauk-sponsorship-2026
```

---

## Troubleshooting

### "fatal: not a git repository"
Run: `git init`

### Files not showing up
```bash
git status           # Check what's staged
git add .            # Add all files
git commit -m "Add files"
git push origin main
```

### Pages not live
1. Check **Settings** → **Pages** is enabled
2. Wait 2-3 minutes for deployment
3. Check branch is "main" and folder is "/root"

---

## Next Steps

1. ✅ Create GitHub account
2. ✅ Create repository
3. ✅ Upload files (via web or command line)
4. ✅ Enable GitHub Pages (optional)
5. ✅ Share the link with colleagues
6. ✅ Update as needed

---

## Additional Resources

- **GitHub Help**: https://docs.github.com
- **GitHub Pages Guide**: https://pages.github.com
- **Git Commands**: https://git-scm.com/docs
- **Markdown Guide** (for README): https://guides.github.com/features/mastering-markdown/

---

**Questions?** Contact Carole Spiers MBE at chair@isma.org.uk

Happy sponsoring! 🚀

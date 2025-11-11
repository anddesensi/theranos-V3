# 🚀 Upload to GitHub - Quick Guide

## Files to Upload

Upload these files to your GitHub repository:

1. **`index.html`** - Your main Theranos investigation page (rename `theranos-case-investigation.html` to `index.html`)
2. **Optional**: Any additional HTML files you want to include

## Step-by-Step Instructions

### Option 1: Upload via GitHub Website (Easiest)

1. **Create a GitHub account** (if you don't have one)
   - Go to https://github.com/signup

2. **Create a new repository**
   - Go to https://github.com/new
   - Repository name: `theranos-investigation` (or any name you prefer)
   - Make it **Public**
   - Check "Add a README file"
   - Click "Create repository"

3. **Upload your files**
   - Click "Add file" → "Upload files"
   - Drag and drop `index.html` (the renamed theranos-case-investigation.html)
   - Click "Commit changes"

4. **Enable GitHub Pages**
   - Go to your repository Settings
   - Scroll down to "Pages" section (left sidebar)
   - Under "Source", select "Deploy from a branch"
   - Select branch: **main** (or master)
   - Select folder: **/ (root)**
   - Click "Save"

5. **View your page online**
   - Wait 1-2 minutes for deployment
   - Your page will be live at: `https://[your-username].github.io/[repo-name]/`
   - Example: `https://johndoe.github.io/theranos-investigation/`

### Option 2: Use the Upload Interface

1. Open `github-upload-interface.html` in your browser
2. Follow the on-screen instructions
3. Enter your GitHub credentials
4. Upload directly from the interface

### Option 3: Command Line (For Advanced Users)

```bash
# Navigate to this folder
cd "/Users/andreadesensi/Downloads/FORENSIC ARCHITECTURE"

# Rename the file to index.html
cp theranos-case-investigation.html index.html

# Initialize git
git init

# Add files
git add index.html

# Commit
git commit -m "Initial commit: Theranos investigation page"

# Connect to GitHub (replace with your details)
git remote add origin https://github.com/[YOUR-USERNAME]/[REPO-NAME].git

# Push to GitHub
git branch -M main
git push -u origin main
```

## What Happens Next?

Once uploaded and GitHub Pages is enabled:
- Your page will be live at: `https://[username].github.io/[repo-name]/`
- It will update automatically when you push changes
- It's completely free hosting
- You can use a custom domain if you want

## Troubleshooting

**Page not showing?**
- Wait 2-5 minutes after enabling GitHub Pages
- Make sure the file is named `index.html`
- Check that the repository is public
- Verify GitHub Pages is enabled in Settings

**Need help?**
- GitHub Pages documentation: https://pages.github.com/
- GitHub support: https://support.github.com/

## Files in This Folder

- `theranos-case-investigation.html` - Your main investigation page (rename to index.html)
- `github-upload-interface.html` - Web interface for uploading
- `cartography-of-genocide.html` - Reference template
- `theranos-investigation.html` - Alternative version

## Quick Start (Absolute Simplest Way)

1. Go to https://github.com/new
2. Name: `theranos-investigation`
3. Public, Add README ✓
4. Create repository
5. Click "uploading an existing file"
6. Rename `theranos-case-investigation.html` to `index.html`
7. Drag `index.html` to the upload area
8. Commit changes
9. Settings → Pages → Source: main branch → Save
10. Visit: `https://[your-username].github.io/theranos-investigation/`

Done! 🎉

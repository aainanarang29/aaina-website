# Push to GitHub - Instructions

## Step 1: Create Repository on GitHub

1. Go to https://github.com/new
2. Repository name: `aaina-narang-website` (or any name you prefer)
3. Choose **Public** or **Private**
4. **DO NOT** initialize with README, .gitignore, or license (we already have files)
5. Click "Create repository"

## Step 2: Connect and Push

After creating the repo, GitHub will show you commands. Run these in your terminal:

```bash
cd "/Users/ainanarang/Website aaina"
git remote add origin https://github.com/YOUR_USERNAME/aaina-narang-website.git
git branch -M main
git push -u origin main
```

Replace `YOUR_USERNAME` with your actual GitHub username.

## Alternative: Using SSH

If you prefer SSH:

```bash
git remote add origin git@github.com:YOUR_USERNAME/aaina-narang-website.git
git branch -M main
git push -u origin main
```

# Chinese Learner - Pinyin Dictionary App

A web app that lets users search for Chinese words by pinyin pronunciation (with or without tone marks).

## Files Included

- `index.html` - The complete app (HTML, CSS, and JavaScript)
- `vercel.json` - Vercel configuration file
- `README.md` - This file

## How to Deploy to Vercel + GitHub

### Step 1: Create a folder on your computer
```bash
mkdir chinese-learner
cd chinese-learner
```

### Step 2: Add these files to the folder
- Copy `index.html` into the folder
- Copy `vercel.json` into the folder

Your folder structure should look like:
```
chinese-learner/
├── index.html
└── vercel.json
```

### Step 3: Initialize Git and push to GitHub

```bash
git init
git add .
git commit -m "Initial commit: Chinese learner app"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/chinese-learner.git
git push -u origin main
```

**Replace `YOUR_USERNAME` with your actual GitHub username**

### Step 4: Deploy on Vercel

1. Go to https://vercel.com/dashboard
2. Click **"Add New..."** → **"Project"**
3. Click **"Import Git Repository"**
4. Find and select `chinese-learner`
5. Click **"Deploy"**

Your app will be live at: `chinese-learner-xxxxx.vercel.app`

## Features

- 🔍 Search Chinese words by pinyin
- 💡 Tones are optional (ma, mā, má, mǎ, mà all work)
- 🇨🇳 Shows simplified and traditional characters
- 📚 Displays English definitions
- 📱 Fully responsive design
- ⚡ Fast, modern interface

## Usage

1. Enter a pinyin word in the search box
2. Click "Search" or press Enter
3. Browse matching words and their definitions

## Technologies

- HTML5
- CSS3 (responsive design)
- Vanilla JavaScript (no dependencies)
- CEDICT dictionary API

## Notes

- The app uses free public dictionary APIs (MDBG/CEDICT)
- No backend server needed
- Works offline once loaded (except search requires internet)

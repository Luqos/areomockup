# Deploy to Vercel — Quick Guide

## Prerequisites
- A [Vercel](https://vercel.com) account (sign up free with GitHub, GitLab, or email)
- Git installed on your machine (or you can use Vercel's drag-and-drop)

## Option 1: Deploy via Git (Recommended)

### 1. Initialize a Git repository (if not already done)
```bash
git init
git add -A
git commit -m "Initial commit"
```

### 2. Push to GitHub / GitLab / Bitbucket
Create a new repository on GitHub, then:

```bash
git remote add origin https://github.com/YOUR_USERNAME/areo-events.git
git branch -M main
git push -u origin main
```

### 3. Import to Vercel
1. Go to [vercel.com/new](https://vercel.com/new)
2. Click **"Continue with GitHub"** (or your provider) and authorise
3. Select your `areo-events` repository
4. Vercel will auto-detect it as a static project — **no build settings needed**
5. Click **"Deploy"**

That's it. Vercel will deploy instantly and give you a URL like `areo-events.vercel.app`.

## Option 2: Deploy via Drag-and-Drop (No Git)

1. Go to [vercel.com/new](https://vercel.com/new)
2. Under **"Deploy with Vercel"**, click the **"Upload"** folder icon (or drag)
3. Select the folder containing your `index.html` file (and this guide if you want)
4. Vercel will upload and deploy — you'll get a live URL within seconds

## Setting a Custom Domain (Optional)

1. In your Vercel project dashboard, go to **Settings → Domains**
2. Enter your domain (e.g., `areoevents.com`)
3. Follow Vercel's DNS configuration instructions for your registrar
4. Vercel provisions SSL automatically

## Notes
- The `index.html` file is self-contained (all CSS/JS via CDN) — no build step required
- Vercel serves static files directly — zero configuration needed
- Every push to your main branch will auto-deploy a new version

---

Your landing page is now live on Vercel 🚀
# Deployment Instructions

## Option 1: Deploy to Vercel (Recommended)

Vercel is the fastest and most beginner-friendly option for static sites.

### Steps

1. **Push to GitHub**
   ```bash
   git add .
   git commit -m "Ready for deployment"
   git push origin master
   ```

2. **Go to [Vercel](https://vercel.com)**
   - Sign in with your GitHub account
   - Click **Add New…** > **Project**
   - Find and import the repository `synent-task1-portfolio-harish`
   - Vercel will auto-detect it as a static site
   - Click **Deploy**

3. **Done!**
   - Your site will be live at `https://synent-task1-portfolio-harish.vercel.app`
   - You can configure a custom domain in the Vercel dashboard

### Custom Domain (Optional)

- In your Vercel project dashboard, go to **Settings > Domains**
- Add your custom domain and follow the DNS instructions

---

## Option 2: Deploy to GitHub Pages

GitHub Pages is free and built into every GitHub repository.

### Steps

1. **Push to GitHub**
   ```bash
   git add .
   git commit -m "Ready for GitHub Pages"
   git push origin master
   ```

2. **Enable GitHub Pages**
   - Go to your repository on GitHub
   - Click **Settings** > **Pages**
   - Under **Branch**, select `master` and `/ (root)` as the folder
   - Click **Save**

3. **Done!**
   - Your site will be live at `https://harishgbs.github.io/synent-task1-portfolio-harish/`
   - It may take 1-2 minutes for the first deployment

### Custom Domain (Optional)

- In the same Pages settings, enter your custom domain
- Create a `CNAME` file or configure DNS at your domain provider

---

## Post-Deployment Checklist

- [ ] Test all navigation links
- [ ] Test the contact form submission
- [ ] Verify Open Graph preview on social media (use [opengraph.xyz](https://www.opengraph.xyz/))
- [ ] Test on mobile and tablet devices
- [ ] Verify all external links open correctly
- [ ] Check Lighthouse performance/accessibility scores

## Environment Variables

No environment variables are required for this static portfolio site.

# CelestCal Landing Page

**Status:** Ready for review  
**Voice:** Stardust-energy casual (lowercase, CAPS, "baby" endings)  
**Design:** Shooting stars, smooth animations, mobile-first


## Features

✨ **Animations:**
- Shooting stars background (spawns every 3 seconds)
- Twinkling star dots
- Fade-in on scroll
- Smooth CTA hover effects

🎨 **Design:**
- Dark gradient background (deep purple → midnight blue)
- Warm ivory content sections
- Soft terracotta CTAs
- DM Sans typography
- Mobile-first responsive

💬 **Voice:**
- "finally, a tracker that gets hungrier when you do"
- "your metabolism spikes 10-20% baby — that's BIOLOGY"
- "biology is unhinged"
- lowercase + CAPS for emphasis


## View Locally

```bash
cd ~/Documents/celestcal-landing
open index.html
```

Or use a local server:
```bash
python3 -m http.server 8000
# Open http://localhost:8000
```


## Sections Included

1. **Hero** — "finally, a tracker that gets hungrier when you do"
2. **Problem** — "you're not failing. your body is changing."
3. **Wedge** — Cycle-synced TDEE explanation
4. **How It Works** — Photo → Verify → Done
5. **Features** — Best accuracy, no guilt, voice logging, cycle insights
6. **Pricing** — Free vs Premium, launch offer
7. **FAQ** — 5 common questions
8. **Footer** — CTA + links


## Deploy Options

### Option 1: Vercel (Recommended)

```bash
cd ~/Documents/celestcal-landing
npm install -g vercel
vercel
```

Follow prompts, deploy to celestcal.vercel.app

### Option 2: Netlify

```bash
npm install -g netlify-cli
netlify deploy
```

### Option 3: GitHub Pages

```bash
git add .
git commit -m "Initial landing page"
git remote add origin https://github.com/YOUR_USERNAME/celestcal-landing.git
git push -u origin main
```

Enable GitHub Pages in repo settings.


## Custom Domain

Once deployed, point your domain (celestcal.com) DNS:
- Add CNAME record: `www` → `your-deployment-url.vercel.app`
- Add A record: `@` → Vercel IP


## Next Steps

1. **Review** — Check on mobile + desktop
2. **Get App Store badge** — Replace placeholder CTA with real badge
3. **Add iPhone mockups** — Replace emoji placeholders with actual screenshots
4. **Analytics** — Add Plausible or Google Analytics
5. **Deploy** — Push to production


## What's Placeholder

- iPhone mockup images (using emojis for now)
- App Store badge (using text button)
- Testimonials (can add real ones later)
- Android waitlist form (just link for now)


## Performance

- Tailwind CDN (fast for MVP, can optimize later)
- Lightweight animations (CSS only)
- Lazy load images when added
- Shooting stars pause when tab is inactive (saves CPU)


## Brand Alignment

✅ Stardust-energy casual voice  
✅ Celestial theme (shooting stars, moon emojis)  
✅ Warm color palette  
✅ No guilt messaging  
✅ Science + slang mix  


## Files

- `index.html` — Main landing page (standalone, no build step needed)
- `README.md` — This file


---

Built with love (and ESTROGEN) 🌙

# Insight Photography 📷

Official website for **Insight Photography** — a professional photography studio based in Kasaragod, Kerala, India. Est. 1998.

> Studio Portraits · Weddings · Lifestyle

**Live site:** [your-netlify-url.netlify.app](https://your-netlify-url.netlify.app)

---

## About

This is a static single-page website built to showcase the studio's portfolio, services, and contact information. It requires no backend server — everything runs in the browser.

**Sections included:**
- Hero
- About the studio
- Services (Weddings, Studio Portraits, Lifestyle)
- Portfolio gallery (7 slots)
- Client testimonials
- Enquiry form (powered by Formspree)
- Contact details & social links

---

## Tech Stack

| What | How |
|------|-----|
| Structure | HTML5 |
| Styling | Pure CSS (no frameworks) |
| Interactivity | Vanilla JavaScript |
| Form handling | [Formspree](https://formspree.io) |
| Hosting | [Netlify](https://netlify.com) |
| Fonts | Google Fonts — Playfair Display + Jost |

---

## File Structure

```
insight-photography/
├── insight-photography.html   ← entire website (single file)
├── README.md                  ← you are here
└── images/                    ← add your portfolio photos here
    ├── wedding1.jpg
    ├── wedding2.jpg
    ├── portrait1.jpg
    └── ...
```

---

## Adding Portfolio Photos

1. Put your photos inside an `images/` folder
2. Recommended size: **1200–1500px wide**, compressed with [squoosh.app](https://squoosh.app)
3. Open `insight-photography.html` and find the portfolio section
4. Replace each placeholder block like this:

**Before:**
```html
<div class="pi-bg">
  <span class="pi-ico">💍</span>
  <span class="pi-lbl">Add your photo</span>
</div>
```

**After:**
```html
<img src="images/wedding1.jpg" alt="Wedding Photography"
     style="width:100%;height:100%;object-fit:cover;">
```

5. Update the overlay caption (title and category) to match the photo

---

## Deploying Changes

Once you make any edit (new photo, text change, etc.), push to GitHub:

```bash
git add .
git commit -m "describe what you changed"
git push
```

Netlify is connected to this repo and will **automatically redeploy** within seconds.

---

## Enquiry Form

Form submissions are handled by **Formspree** and delivered to:
📧 `insightwedding@gmail.com`

Formspree endpoint: `https://formspree.io/f/mnjbebwg`

Free plan allows **50 submissions/month**.

---

## Contact & Socials

| | |
|---|---|
| 📍 Address | 1st Floor, Padhoor Complex, New Bus Stand, Kasaragod, Kerala, India |
| 📞 Phone | See live website |
| ✉️ Email | insightwedding@gmail.com |
| 📸 Instagram | [@insight_weddings](https://www.instagram.com/insight_weddings) |
| 📘 Facebook | [Insight Photography](https://www.facebook.com/share/1CEpsSTzi3/) |
| ▶️ YouTube | [@InsightWedding](https://www.youtube.com/@InsightWedding) |
| 💬 WhatsApp | [Chat with us](https://wa.me/919656564444) |

---

## Local Development

No build tools needed. Just open the file in a browser:

```bash
# Option 1 — open directly
open insight-photography.html

# Option 2 — serve locally (avoids some browser restrictions)
npx serve .
# then visit http://localhost:3000
```

---

*Built with care for Insight Photography, Kasaragod · Since 1998*

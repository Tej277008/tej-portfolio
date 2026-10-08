# Tej Bikram Thapa — Multipage Portfolio

A responsive, accessible static portfolio with dedicated pages and a persistent light/dark theme.

## Preview on your Mac

Unzip, open Terminal inside `tej-portfolio`, then run:

```bash
python3 -m http.server 8000
```

Visit http://localhost:8000.

## Pages

- `index.html` — home and large photo
- `about.html` — background
- `skills.html` — detailed skill categories
- `projects.html` — project index
- `stay-wise.html` and `network-anomaly.html` — individual case studies
- `education.html` — education and honors
- `resume.html` — resume information
- `contact.html` — email and LinkedIn

## Before publishing

1. Upload your verified resume PDF and change the resume page to include a download button.
2. Add your GitHub URL and verified repository links.
3. Check all claims and details for accuracy.
4. Deploy the folder to GitHub Pages, Netlify, or Vercel.
5. After choosing your actual public domain, set canonical URLs, generate sitemap.xml, and submit the sitemap in Google Search Console. Google indexing is not guaranteed.

No third-party build dependencies. Google Fonts requires an internet connection.

## Photography update
The homepage uses your local `assets/tej-photo.jpg` as a wide, softly faded background. Other pages display coding/computer photography from Unsplash, which requires internet access in the browser. If a photo cannot load, a styled coding-themed fallback is shown. The light/dark toggle remains available across pages.


Project images in assets/*-concept.svg are ORIGINAL ILLUSTRATIVE MOCKUPS, not actual app screenshots or verified charts. Replace with genuine screenshots and results when available. Project case studies avoid invented performance claims.

StayWise live demo: https://staywise-tau.vercel.app/ . Invoicly is documented from user supplied README; repository URL is not verified. in invoicly.html the dashboard image is illustrative.

Invoicly source repository: https://github.com/axp8948/invoicly (public, verified).

Resume-derived details were added to Education, Skills, Projects, and Resume pages. The included PDF is an older resume supplied by the owner and should be replaced before publication.

Blog: blog.html lists planned topics, clearly labeled as planned. Publish real articles as separate HTML pages, add dates only on publication, and link them from blog.html.

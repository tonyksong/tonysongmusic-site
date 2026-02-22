# Tony Song — Jazz Guitarist Portfolio

Personal portfolio website for Tony Song, a jazz & contemporary guitarist based in NYC.

## Deployment

This site is designed for **GitHub Pages**. To deploy:

1. Push this repository to GitHub
2. Go to **Settings → Pages**
3. Set source to **Deploy from a branch** → `main` (root `/`)
4. The site will be live at your GitHub Pages URL

### Custom Domain

The `CNAME` file is configured for `www.tonysongmusic.com`. To use a custom domain:

1. In your domain registrar, add a CNAME record pointing `www` to `<username>.github.io`
2. Add A records pointing to GitHub Pages IPs:
   - `185.199.108.153`
   - `185.199.109.153`
   - `185.199.110.153`
   - `185.199.111.153`
3. In GitHub repo Settings → Pages, enter your custom domain

### Contact Form

The contact form currently uses a placeholder action URL. To make it functional:

1. Sign up at [Formspree](https://formspree.io) (free tier available)
2. Create a new form and get your form endpoint
3. Replace `https://formspree.io/f/placeholder` in `index.html` with your actual endpoint

## Tech Stack

- Pure HTML, CSS, JavaScript (no build step required)
- Google Fonts (Playfair Display + Inter)
- Mobile-first responsive design
- Intersection Observer for scroll animations

# Izumi — Personal Portfolio

A clean, minimal personal portfolio site built with HTML, CSS, and vanilla JS. Hosted on GitHub Pages.

## How to deploy

1. Create a new GitHub repo named `yourusername.github.io`
2. Upload these three files: `index.html`, `style.css`, `script.js`
3. Go to repo **Settings → Pages → Source → Deploy from branch → main**
4. Your site will be live at `https://yourusername.github.io` in ~1 minute

## To customize

- **Your name:** Replace "Izumi" with your actual name in `index.html` (nav logo, hero, footer)
- **Email:** Find `your@email.com` and replace
- **GitHub/LinkedIn/YouTube links:** Search for placeholder URLs and update
- **Project GitHub links:** Replace `href="#"` in each card with your actual repo URLs
- **Research paper link:** Update when published
- **Blog posts:** Replace the placeholder `.blog-item` with real posts using the same structure

## File structure

```
index.html   ← all content and structure
style.css    ← all styles and design tokens
script.js    ← mobile nav, scroll reveal, active nav highlight
```

## Adding a custom domain later

1. Buy domain from Namecheap or Porkbun (~$10/year)
2. In your repo root, create a file called `CNAME` containing just your domain (e.g. `izumi.me`)
3. In your domain registrar's DNS settings, add these A records:
   ```
   185.199.108.153
   185.199.109.153
   185.199.110.153
   185.199.111.153
   ```
4. Wait 10–30 minutes. GitHub handles HTTPS automatically.

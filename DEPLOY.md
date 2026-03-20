# Deploying SPSN site (static)

This folder is a static site (HTML/CSS). You can deploy it on any static host.

## Option A: Netlify (fastest)
1. Go to https://app.netlify.com/drop
2. Drag-and-drop the **spsn-site/** folder contents (index.html + styles.css).
3. Netlify will give you a live URL.

## Option B: Cloudflare Pages
1. Create a GitHub repo and push this folder.
2. In Cloudflare Pages: Create project → connect repo → build command: **none** → output: **/**.

## Local preview
From the workspace root:

```bash
cd spsn-site
python3 -m http.server 5173
```

Then open: http://localhost:5173

## Update contact details
- WhatsApp link is in multiple places:
  - `https://wa.me/260978518880`
- Email:
  - `mailto:luasonda@gmail.com`

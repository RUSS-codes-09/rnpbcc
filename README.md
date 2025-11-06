# rnpbcc
Static Website for RNPBCC.
# RNP Business Consulting Corp. — Static Site

Simple static website for RNP Business Consulting Corp. Built with plain HTML, CSS and a small amount of client-side JavaScript (EmailJS for contact form, JSON-LD schema).

## Features
- Responsive static layout: header, hero, services, about, contact, footer
- Service cards with image icons
- Contact form using EmailJS
- JSON-LD Organization schema (update URL after deploy)
- Lightweight, no build step required

## File overview
- `rnp.html` — main site file (HTML, CSS, JS inline)
- Images referenced in the markup: `RNP copy.png`, `background.jpg`, `group.jpg`, `ac1.jpg`, `BIR1.jpg`, `tax.jpg`, `Consultation.jpg`, `Audit.jpg`, `payroll.jpg`
- (Optional) `assets/icons/` — suggested location for service icon images if you reorganize

## Run locally
1. Clone or copy the project folder to your machine.
2. Open `rnp.html` in your browser, or serve via a simple HTTP server (recommended to avoid mixed-content / JS file-loading issues):

PowerShell / Command Prompt (Python):
```bash
# from project folder
python -m http.server 8000
# open http://localhost:8000/rnp.html
```

Node (serve):
```bash
npx serve .
```

## Deploy (free options)
- GitHub Pages
  - Create repo, push code, enable Pages from `main` branch (or `gh-pages`).
  - Site URL: `https://<username>.github.io/<repo>/`
- Netlify
  - Drag & drop site folder or connect repo — automatic deploys + SSL.
- Vercel
  - `vercel` CLI or connect repo for instant deployment.

After deploy, update the JSON-LD `url` field in the script to your public site URL.

## EmailJS & Security
- Current EmailJS keys and IDs are in `rnp.html`. Replace with your own EmailJS public key, service ID and template ID.
- Avoid committing private keys or server-side secrets to public repos — email sending keys are public but treat templates/service IDs carefully.
- For production, consider server-side form handling or a secure serverless function.

## Tips / To-do
- Move inline CSS/JS to separate files for better maintainability.
- Optimize images and use SVGs for service icons.
- Fix small HTML issues (duplicate/mis-formed attributes like `id="about us"`).
- Add accessibility attributes (alt text, aria labels) and form validation messages.

## Contact
For further edits or deployment help, open the project in VS Code and run the commands above.// filepath: c:\Users\Russ\Desktop\RNPWEB\rnpbcc (3)\README.md

# RNP Business Consulting Corp. — Static Site

Simple static website for RNP Business Consulting Corp. Built with plain HTML, CSS and a small amount of client-side JavaScript (EmailJS for contact form, JSON-LD schema).

## Features
- Responsive static layout: header, hero, services, about, contact, footer
- Service cards with image icons
- Contact form using EmailJS
- JSON-LD Organization schema (update URL after deploy)
- Lightweight, no build step required

## File overview
- `rnp.html` — main site file (HTML, CSS, JS inline)
- Images referenced in the markup: `RNP copy.png`, `background.jpg`, `group.jpg`, `ac1.jpg`, `BIR1.jpg`, `tax.jpg`, `Consultation.jpg`, `Audit.jpg`, `payroll.jpg`
- (Optional) `assets/icons/` — suggested location for service icon images if you reorganize

## Run locally
1. Clone or copy the project folder to your machine.
2. Open `rnp.html` in your browser, or serve via a simple HTTP server (recommended to avoid mixed-content / JS file-loading issues):

PowerShell / Command Prompt (Python):
```bash
# from project folder
python -m http.server 8000
# open http://localhost:8000/rnp.html
```

Node (serve):
```bash
npx serve .
```

## Deploy (free options)
- GitHub Pages
  - Create repo, push code, enable Pages from `main` branch (or `gh-pages`).
  - Site URL: `https://<username>.github.io/<repo>/`
- Netlify
  - Drag & drop site folder or connect repo — automatic deploys + SSL.
- Vercel
  - `vercel` CLI or connect repo for instant deployment.

After deploy, update the JSON-LD `url` field in the script to your public site URL.

## EmailJS & Security
- Current EmailJS keys and IDs are in `rnp.html`. Replace with your own EmailJS public key, service ID and template ID.
- Avoid committing private keys or server-side secrets to public repos — email sending keys are public but treat templates/service IDs carefully.
- For production, consider server-side form handling or a secure serverless function.

## Tips / To-do
- Move inline CSS/JS to separate files for better maintainability.
- Optimize images and use SVGs for service icons.
- Fix small HTML issues (duplicate/mis-formed attributes like `id="about us"`).
- Add accessibility attributes (alt text, aria labels) and form validation messages.

## Contact
For further edits or deployment help, open the project in VS Code and run the commands above.

# Deploy Dr. Farahnaz Hosseini's website

## Files
- `index.html` — website content
- `styles.css` — design and responsive layout
- `script.js` — small footer year script
- `assets/farahnaz-headshot.png` — profile photo
- `assets/Farahnaz_Hosseini_CV.pdf` — CV download

## Option A: Deploy with Vercel
1. Go to https://vercel.com and sign in with GitHub or email.
2. Create a new project.
3. Upload/import this folder as a static site.
4. After deployment, open Project Settings → Domains.
5. Add `farahnazhosseini.com` and `www.farahnazhosseini.com`.
6. Vercel will show the exact DNS records to add in Network Solutions.

Common Vercel DNS records:
- A record: Host `@` → `76.76.21.21`
- CNAME record: Host `www` → `cname.vercel-dns.com`

## Network Solutions DNS steps
1. Log in to Network Solutions.
2. Open Domains → select `farahnazhosseini.com`.
3. Go to Advanced Tools → Advanced DNS Records → Manage.
4. Add or edit the A and CNAME records shown by Vercel.
5. Wait for DNS propagation. It may take a few minutes to 24–48 hours.

## Suggested future edits
- Add your final LinkedIn URL.
- Add direct links/DOIs for publications.
- Add a Nexora AI page or subdomain later: `nexora.farahnazhosseini.com`.

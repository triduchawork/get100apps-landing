# Get100Apps Landing Page

## Quick Deploy to Vercel

1. Download both files: `index.html` and `vercel.json`
2. Put them in a folder called `get100apps`
3. In Vercel dashboard, click "Add New" → "Project"
4. Drag and drop the folder
5. Click "Deploy"

## After Deploy

1. Get your live URL (will be something like `get100apps.vercel.app`)
2. Go to your domain registrar (where you bought get100apps.com)
3. Add these DNS records:

**A Record:**
- Name: `@`
- Value: `76.76.21.21`

**CNAME Record:**
- Name: `www`
- Value: `cname.vercel-dns.com`

4. In Vercel, go to your project → Settings → Domains
5. Add `get100apps.com` and `www.get100apps.com`
6. Wait 5-10 minutes for DNS to propagate

## Done!

Your site will be live at get100apps.com

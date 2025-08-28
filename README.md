# Mark Herz – Classical Guitarist & Teacher

This repository hosts the official website of Mark Herz.

## Deployment

1. Push code to GitHub.
2. Go to **Settings → Pages**.
3. Set **Source** = `main` branch, `/ (root)`.
4. Add your custom domain `www.markherz.ca`.
5. On GoDaddy, update DNS:
   - Add A records:
     ```
     @   A   185.199.108.153
     @   A   185.199.109.153
     @   A   185.199.110.153
     @   A   185.199.111.153
     ```
   - Add CNAME record:
     ```
     www   CNAME   yourusername.github.io
     ```
6. Enable HTTPS in GitHub Pages settings.

Your site will resolve at `www.markherz.ca`.

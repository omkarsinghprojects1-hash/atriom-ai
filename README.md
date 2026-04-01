# Atriom-AI Website

Official website for **Atriom-AI** — enterprise AI solutions for Education, Healthcare, Real Estate, Logistics, and Industry.

## 🚀 Hosting on GitHub Pages

### Quick Setup

1. **Fork or push this repo** to your GitHub account
2. Go to **Settings → Pages**
3. Under *Source*, select `Deploy from a branch`
4. Choose `main` branch and `/ (root)` folder
5. Click **Save** — your site will be live at `https://<your-username>.github.io/<repo-name>`

### Custom Domain Setup

1. In the repo root, a `CNAME` file is already present — edit it with your domain name (e.g. `atriom-ai.com`)
2. In your domain registrar's DNS settings, add:
   - **A records** pointing to GitHub Pages IPs:
     ```
     185.199.108.153
     185.199.109.153
     185.199.110.153
     185.199.111.153
     ```
   - Or a **CNAME record**: `www` → `<your-username>.github.io`
3. Back in GitHub → Settings → Pages, enter your custom domain and enable **Enforce HTTPS**

## 📁 File Structure

```
/
├── index.html       ← Main website (single-file, no build step needed)
├── CNAME            ← Custom domain configuration
└── README.md        ← This file
```

## 📬 Contact

All enquiries → **info@atriom-ai.com**

# NomadDesk — WFH & Digital Nomad Gear Reviews

A static affiliate site targeting the Amazon Associates US programme. Built for GitHub Pages deployment.

## Site structure

```
nomad-desk/
├── index.html               # Homepage with hero, categories, featured products
├── reviews.html             # All reviews with category filtering
├── setup-guide.html         # Interactive quiz → personalised gear list
├── about.html               # About page (required by Amazon Associates)
├── affiliate-disclosure.html # Required by Amazon TOS + FTC guidelines
├── privacy.html             # Privacy policy (required by Amazon TOS)
├── css/style.css            # All styles
├── js/main.js               # Nav toggle + shared JS
└── .github/workflows/deploy.yml  # Auto-deploy to GitHub Pages
```

## Deploy to GitHub Pages

### Option A — GitHub Actions (recommended)

1. Push this repo to GitHub (any repo name works; `nomad-desk` is clean)
2. Go to **Settings → Pages → Source** → select **GitHub Actions**
3. Push to `main` — the workflow auto-deploys
4. Your site will be live at `https://YOUR-USERNAME.github.io/nomad-desk/`

### Option B — Branch deploy (simpler)

1. Push to GitHub
2. Go to **Settings → Pages → Source** → select **Deploy from a branch** → `main` → `/ (root)`
3. GitHub Pages will build automatically

## Before applying to Amazon Associates

1. **Replace `YOUR-TAG-20`** in all HTML files with your actual Amazon Associates tag
2. **Update the email address** `hello@nomaddesk.example.com` in about.html and privacy.html
3. **Add at least 10 original articles** — you can use the product pages as a base and expand each into a 800–1000 word review
4. **Verify all required pages exist**: About ✓, Contact (add one), Privacy Policy ✓, Affiliate Disclosure ✓
5. **Check the site is publicly accessible** before submitting the Associates application

## Finding your affiliate tag

After Amazon Associates approves your account:
1. Go to Associates Central → Account Settings → Manage Your Tracking IDs
2. Your tag looks like `yourname-20`
3. Run a find & replace on `YOUR-TAG-20` across all HTML files

## The 3-sale rule

You must make 3 qualifying sales within 180 days of account approval. Before applying:
- Make sure the site is live and public
- Have at least 100+ social media followers or existing traffic
- Consider sharing the Setup Guide first — it's a high-conversion page

## Customisation checklist

- [ ] Replace site name "NomadDesk" with your own brand
- [ ] Update `YOUR-TAG-20` with real Associates tag
- [ ] Replace placeholder email addresses
- [ ] Add a Contact page (recommended by Amazon)
- [ ] Add Google Analytics or similar for traffic reporting
- [ ] Add Schema.org Product markup for SEO (see schema.org/Product)
- [ ] Connect a custom domain (Settings → Pages → Custom domain)

# Guangzhou Suide Trading Co., Ltd. Website

This is a pure static company website for Guangzhou Suide Trading Co., Ltd. It is designed for GitHub Pages, company profile verification, Google Play developer information, D-U-N-S/business verification support, and hosting legal pages such as the Privacy Policy.

## Pages

- `index.html` - Company homepage
- `privacy-policy.html` - Privacy Policy for mobile applications and digital products
- `terms.html` - General Terms of Service
- `CNAME` - Custom domain configuration for GitHub Pages

## Local Preview

Because this site uses only static HTML, CSS, and JavaScript, you can preview it directly by opening `index.html` in a browser.

For a local server preview, run one of the following commands from the project root:

```bash
python3 -m http.server 8080
```

Then open:

```text
http://localhost:8080
```

## Deploy to GitHub Pages

1. Push this repository to GitHub.
2. In the repository settings, open **Pages**.
3. Choose deployment from the `main` branch and the repository root.
4. Save the settings.
5. If using the custom domain, set it to:

```text
suidetrading.com
```

The included `CNAME` file already contains the custom domain.

## DNS Notes

For the custom domain `suidetrading.com`, configure DNS according to GitHub Pages requirements. Typically this means adding GitHub Pages A records for the apex domain and, if needed, a CNAME record for `www`.

Refer to the official GitHub Pages custom domain documentation for the current DNS records.

## Updating Company Information

Common company details are written directly in the HTML files:

- Company name: `Guangzhou Suide Trading Co., Ltd.`
- Website: `https://suidetrading.com`
- Developer email: `developer@suidetrading.com`
- Support email: `support@suidetrading.com`

If any company information changes, update it in `index.html`, `privacy-policy.html`, and `terms.html`.

## Technical Details

- No build step required
- No external dependencies
- Responsive layout for desktop and mobile
- Relative links compatible with GitHub Pages and the custom domain
- Lightweight JavaScript only for the mobile navigation menu

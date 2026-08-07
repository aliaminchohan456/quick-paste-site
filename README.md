# Quick Paste Website

Official website and legal-information hub for **Quick Paste Keyboard**, an Android productivity app for creating, organizing, syncing, and quickly pasting reusable text snippets.

[![Live website](https://img.shields.io/badge/Live_Website-4D8DF7?style=for-the-badge&logo=githubpages&logoColor=white)](https://aliaminchohan456.github.io/quick-paste-site/)
[![Google Play](https://img.shields.io/badge/Google_Play-202124?style=for-the-badge&logo=googleplay&logoColor=white)](https://play.google.com/store/apps/details?id=app.quickpaste.keyboard)
[![GitHub Pages](https://img.shields.io/badge/Hosted_on-GitHub_Pages-222222?style=for-the-badge&logo=github&logoColor=white)](https://pages.github.com/)

## Live pages

- [Product website](https://aliaminchohan456.github.io/quick-paste-site/)
- [Privacy policy](https://aliaminchohan456.github.io/quick-paste-site/privacy_policy.html)
- [Data deletion instructions](https://aliaminchohan456.github.io/quick-paste-site/data-deletion.html)

## About the website

The site explains Quick Paste's core features, privacy approach, optional cloud sync, account and data-deletion controls, and one-time developer-support purchases. It is intentionally lightweight and uses plain HTML and CSS so it loads quickly and remains easy to audit and maintain.

### Highlights

- Responsive layouts for phones, tablets, and desktop screens
- Light and dark color-scheme support
- Quick Paste's blue visual identity and consistent shared components
- Accessible skip links, visible keyboard focus, semantic headings, and large touch targets
- Reduced-motion support for users who request it
- Clear privacy and data-deletion navigation
- No JavaScript framework, build step, tracking script, or cookie banner required

## Project structure

```text
quick-paste-site/
├── index.html              # Product landing page
├── privacy_policy.html     # Privacy policy
├── data-deletion.html      # Account and data-deletion guide
├── legal.css               # Shared styling for legal pages
└── README.md               # Project documentation
```

## Local preview

The pages can be opened directly in a browser. For a more accurate local preview, serve the directory over HTTP:

```bash
python -m http.server 8080
```

Then visit [http://localhost:8080](http://localhost:8080).

## Deployment

The website is deployed through **GitHub Pages** from the repository's `main` branch. Merging an approved change into `main` triggers the Pages deployment automatically.

Before publishing a change, verify:

1. All three pages open successfully.
2. Internal navigation and section links work.
3. There is no horizontal overflow at mobile, tablet, or desktop widths.
4. Privacy and data-deletion wording still matches the current app behavior.
5. Google Play and contact links are correct.

## Privacy and maintenance

When Quick Paste adds or changes authentication, cloud storage, analytics, billing, account deletion, or third-party services, review both legal pages before releasing the app update. Product descriptions must stay factual, and Google Play prices are always displayed by the app using localized Play Billing data.

## Related project

- [Quick Paste Keyboard on GitHub](https://github.com/aliaminchohan456/Quick_paste_Keyboard)
- [Quick Paste Keyboard on Google Play](https://play.google.com/store/apps/details?id=app.quickpaste.keyboard)

## Contact

For privacy questions, data-deletion assistance, or website corrections, email [contact.quickpaste@gmail.com](mailto:contact.quickpaste@gmail.com).

---

© 2026 Quick Paste. All rights reserved.

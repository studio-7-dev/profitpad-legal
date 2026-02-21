# ProfitPad Legal Documentation

This repository contains the legal policies and terms for the ProfitPad mobile application.

## 📄 Documents

- **[Privacy Policy](privacy.md)** — How we collect, use, and protect your data
- **[Terms of Service](terms.md)** — Our terms and conditions for using ProfitPad

## 🔗 Hosted URLs

These documents are hosted on GitHub Pages and served at:

- Privacy Policy: `https://studio-7-dev.github.io/profitpad-legal/privacy`
- Terms of Service: `https://studio-7-dev.github.io/profitpad-legal/terms`

*Note: These URLs will be embedded in the ProfitPad mobile app and linked in App Store/Play Store listings.*

## 📝 Document Information

| Document | Last Updated | Status |
|----------|--------------|--------|
| Privacy Policy | February 21, 2026 | ✅ Active |
| Terms of Service | February 21, 2026 | ✅ Active |

## ⚙️ Configuration

### GitHub Pages Setup

This repository is configured with GitHub Pages using the `main` branch as the source.

**Settings:**
- Source: `main` branch
- Custom domain: (optional)
- HTTPS: Enabled

### How Files Are Served

- `privacy.md` → Served as plain markdown at `/privacy`
- `terms.md` → Served as plain markdown at `/terms`

GitHub Pages automatically renders markdown files with GitHub's Markdown styling.

## 📱 Integration with ProfitPad App

The URLs are configured in the app at:
- File: `components/LegalLinks.js`
- Links:
  - `https://studio-7-dev.github.io/profitpad-legal/privacy`
  - `https://studio-7-dev.github.io/profitpad-legal/terms`

When users tap "Privacy Policy" or "Terms of Service" in the app, these URLs open in their browser.

## 🔄 How to Update

To update the legal documents:

1. Edit `privacy.md` or `terms.md` in this repository
2. Update the "Last Updated" date in the document
3. Commit and push changes to `main` branch
4. Changes are automatically live on GitHub Pages

Example:
```bash
# Edit a file
nano privacy.md

# Commit changes
git add privacy.md
git commit -m "Update privacy policy with new data retention info"
git push origin main
```

## ✅ Validation

Before publishing updates, verify:
- [ ] Document is valid markdown
- [ ] All links are active
- [ ] Contact information is current
- [ ] Dates are accurate
- [ ] Terms match your actual practices

## 📋 Checklist for App Store Submission

- [ ] Privacy Policy URL configured in app
- [ ] Terms of Service URL configured in app
- [ ] Both documents are live and accessible
- [ ] URLs are submitted in App Store Connect
- [ ] URLs are submitted in Google Play Console
- [ ] Links work from the app
- [ ] Documents load properly on mobile

## 🆘 Support

For questions about these legal documents, contact:
- Email: legal@profitpad.app
- Issues: Create an issue in this repository

---

**ProfitPad Legal Repository** — https://github.com/studio-7-dev/profitpad-legal

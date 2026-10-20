# Oasis Bazaar

Premium stationery, paper, gifting and packaging catalogue for Om Nidhi Trading Pvt. Ltd., Mumbai.

## Website files

The complete static website is in `dist/`. No dependency installation or build step is required.

- `dist/index.html`: website sections and enquiry forms
- `dist/style.css`: responsive styling
- `dist/app.js`: catalogue data, search, category and gift-box filters, Diwali Finds and WhatsApp enquiries
- `dist/catalogue.json`: extracted 2026 catalogue reference data; the live page currently uses the catalogue embedded in app.js
- `dist/assets/`: logo, catalogue product photos and store photos

## Preview locally

From the repository folder, run:

```sh
python3 -m http.server 8000 --directory dist
```

Open http://localhost:8000 in your browser.

## Current private review website

https://oasis-bazaar.bronzeegret.chatgpt.site

This repository contains a copy of the current site. GitHub and the hosted review site do not automatically sync. Changes must be applied to both through their respective publishing workflows.

## Hosting elsewhere

Configure a static host to publish the `dist` directory, with no build command. GitHub repository privacy does not automatically protect a separately hosted website; keep hosting access private until the site is approved. No GitHub Pages deployment is configured here.

## Enquiries

Product and wholesale forms open a prefilled message at WhatsApp number +91 98675 18902. Visitors review and send their message in WhatsApp. Prices, cart and checkout are intentionally absent.

## Images and product details

Product photos and specifications were sourced from the supplied Oasis Product Catalogue 2026. Some products, including jar and collapsible gift boxes, still use labelled illustrative placeholders. Confirm current sizes, finishes and availability with the business.

Store photographs are credited in the website to Om Nidhi Trading Pvt Ltd and A N via the business's Google Maps listing. Preserve those credits.

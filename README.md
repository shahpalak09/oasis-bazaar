# Oasis Bazaar

Premium stationery, paper, gifting and packaging catalogue for Om Nidhi Trading Pvt. Ltd., Mumbai.

## Pages

- `dist/index.html`: short homepage previews and gift-box slideshow
- `dist/collections.html`: Office, School and Gifting collections
- `dist/diwali.html`: Diwali Finds with a searchable gifting catalogue
- `dist/catalogue.html`: complete searchable catalogue and product enquiries
- `dist/about.html`: company story
- `dist/contact.html`: store photos, directions and contact information
- `dist/wholesale.html`: wholesale enquiry and video-call request forms
- `dist/gallery.html`, `dist/faq.html`, `dist/delivery.html`: additional information

## Preview

No installation or build is needed. Run:

```sh
python3 -m http.server 8000 --directory dist
```

Open http://localhost:8000. On a static host, publish the `dist` directory without a build command.

## Private review site

https://oasis-bazaar.bronzeegret.chatgpt.site

GitHub contains a copy of the website. There is no automatic sync with the hosted review site. Repository privacy does not control a separate host's access; keep hosting private until approved. No GitHub Pages deployment is configured.

## Editing

`dist/style.css` contains styling. `dist/app.js` holds shared catalogue data, filtering, product detail dialogs, slideshow and WhatsApp forms. `dist/catalogue.json` is an extracted catalogue reference; the app currently uses the embedded data in app.js. Images are stored in `dist/assets/`.

## Enquiries and video calls

Product, wholesale and video-call request forms open prefilled WhatsApp messages to +91 98675 18902. Visitors review and send messages themselves. Video-call requests include the preferred date, time and discussion; the team confirms availability and supplies the call link. This is not an automatic calendar booking. Prices, cart and checkout are intentionally absent.

## Photography

Catalogue images come from the supplied Oasis Product Catalogue 2026. Some products, including jar and collapsible gift boxes, still have labelled placeholders. Store photographs are credited in the website to Om Nidhi Trading Pvt Ltd and A N via Google Maps. Preserve those credits.

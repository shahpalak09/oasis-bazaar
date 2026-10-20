# Oasis Bazaar

Premium stationery, paper, gifting and packaging catalogue for Om Nidhi Trading Pvt. Ltd., Mumbai.

## Run locally

```sh
python3 -m http.server 8000 --directory dist
```

Open http://localhost:8000. No installation or build is needed. Publish `dist` on a static host.

## Pages

Home, Collections, Diwali Finds, Catalogue, Our Story, Visit Us, Wholesale & Video Calls, Gallery, FAQ and Delivery Information each have separate HTML pages in `dist/`.

The catalogue, filters, slideshow and WhatsApp interactions live in `dist/app.js`. Styles are in `dist/style.css` and media in `dist/assets/`.

## Selected gift boxes

Only eight gift-box designs from the supplied box PDF have been added after comparison with the four supplied stock photographs: articles 521, 574, 2046, 5088, 502, 501, 673 and J8. They replace the earlier generic box entries. `dist/matched-boxes.json` records these products; live product data is embedded in app.js. Other PDF boxes are intentionally omitted. Enquiries should confirm dimensions and jar inclusion.

## Enquiries

Product, wholesale and video-call forms open a prefilled WhatsApp message to +91 98675 18902. Visitors review and send messages themselves. Video calls are requests; the team confirms the time and call link. There are no prices, cart or checkout.

## Private review site

https://oasis-bazaar.bronzeegret.chatgpt.site

This repository and the hosted review site do not automatically sync. Repository privacy does not control separate hosting access. No GitHub Pages deployment is configured.

## Photos

Product photography comes from supplied Oasis catalogues. Store photographs are credited to Om Nidhi Trading Pvt Ltd and A N via Google Maps; preserve the credits on the site.

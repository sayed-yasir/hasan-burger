# Hasan Burger — V2

## Project structure

- `index.html` — public website and embedded real images
- `style.css` — all website styling
- `script.js` — website logic and the private-by-code `FOOD_CARDS` data
- `README.md` — instructions

## Food cards
There is intentionally **no public add/edit/delete panel**. To add or change a food card, edit the `FOOD_CARDS` array near the top of `script.js`. Then upload the updated `script.js` to your hosting/server.

A static website cannot technically prevent someone from changing a downloaded/local copy in browser developer tools. Those local changes do not change the files on your server. For real server-side protection, keep deployment/repository access private and use authentication/permissions on the hosting platform.

## WhatsApp
The site uses WhatsApp number `0782 200 222` (`93782200222` for WhatsApp links). Visitors can type a message on the site and press **Send to WhatsApp**, or use the direct WhatsApp buttons on food cards.

## Phone numbers
- `0782 200 222`
- `0779 125 959`

## Images
The supplied Hasan Burger images remain embedded as Base64/data URLs, so this project does not require an `assets` folder for the supplied images.

## Important security note
This is a static frontend. It is suitable for a public restaurant website, but it is not a secure CMS. Never put passwords, API keys, database credentials, or other secrets into `index.html` or `script.js`.

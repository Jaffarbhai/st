ST EVENTS — WEBSITE
===================

FILES
  index.html   The complete website (one file). Open it in any browser.
  images/      Put your own event photos here.

PUT IT ONLINE
  Upload the whole folder to any host: Netlify (drag and drop the folder at
  app.netlify.com/drop), Hostinger, cPanel "public_html", GitHub Pages, etc.
  An internet connection is needed for the fonts and animations.

CHANGE YOUR DETAILS
  Open index.html in a text editor (Notepad, VS Code) and search for
  "EDIT YOUR BUSINESS DETAILS HERE". Edit the SITE section:
    whatsapp   923123380876   (country code, digits only)
    phone      0312 3380876
    email      ""             (add one to show it in the footer)
    address    Jinnah Square, Malir, Karachi
    instagram / facebook / tiktok   your profile links

ADD YOUR REAL PHOTOS
  1. Copy photos into the images folder, e.g. images/wedding-1.jpg
  2. In index.html find PHOTOS, STAGES, FLORALS and EVENTS.
  3. Put the file path in that item's src, e.g.
       src: "images/wedding-1.jpg"
  Leave src "" to keep the drawn floral artwork.
  Tip: resize photos to about 1600px wide and save as JPG/WebP (under 400 KB)
  so the site stays fast. Portrait photos suit the About, Gallery and Events
  sections; landscape photos suit the Hero and Signature Stages.

ADD CLIENT REVIEWS
  Find REVIEWS and add real reviews like:
    { quote: "They turned our walima hall into a garden.", name: "Ayesha & Bilal", event: "Walima · 2026" },

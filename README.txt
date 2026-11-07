TN PRODUCTION - WEBSITE FILES (HTML, CSS, JAVASCRIPT ONLY)
===========================================================

WHAT IS IN THIS FOLDER
  index.html ........ Homepage
  shop.html ......... Shop with filters and sorting
  product.html ...... One product page (opened from the shop)
  cart.html ......... Shopping cart and discount codes
  checkout.html ..... Delivery details and payment choice
  contact.html ...... Contact form, WhatsApp, social links
  about.html, faq.html, shipping.html, returns.html, privacy.html, terms.html
  css/style.css ..... Colors and layout (colors are at the top of the file)
  js/config.js ...... YOUR SETTINGS: name, currency, WhatsApp, email, bank details
  js/products.js .... YOUR PRODUCTS AND CATEGORIES
  js/*.js ........... Shop behavior (you do not need to change these)

STEP 1: CHANGE YOUR SETTINGS
  Open js/config.js in any plain text editor (Notepad, TextEdit).
  Change brandName, currency, locale, whatsapp, contactEmail, phone,
  social links, bank details, and flatShippingFee. Save the file.

STEP 2: CHANGE YOUR PRODUCTS
  Open js/products.js. Each product is one block between { and }.
  Copy a whole block to add a product. Delete a block to remove one.
  Replace the placeholder image links with links to your own photos.
  Keep the commas between blocks.

STEP 3: VIEW IT ON YOUR COMPUTER
  Double-click index.html. It opens in your web browser.
  Note: placeholder photos load from the internet (placehold.co).

STEP 4: PUBLISH IT
  Upload every file and folder in this folder to a web host or a
  static hosting service, keeping the same folder structure. Your host
  or service must have index.html at the top level.
  Then connect your domain name following the host's instructions.

IMPORTANT LIMITS OF A STATIC (HTML/CSS/JS) SITE
  - Products are edited in js/products.js, not in a dashboard.
  - Orders are sent to you by WhatsApp or email for confirmation.
    The site does not take card payments.
  - Discount codes are checked in the customer's browser, so they are not secret.
  - Pages with [square brackets] contain placeholders to replace.
  - Customer accounts and a newsletter service are not included.

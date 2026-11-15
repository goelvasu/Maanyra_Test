# Maanyra Website (version 2, redesigned)

Open `index.html` in any browser to use the site. To put it online, upload `index.html` to any web host (Netlify, GitHub Pages, your domain host).

## What is included
- **Home**: three cards for Gift & Stationery Shop, Handlooms, Tuition Classes
- **Gift & Stationery Shop** and **Handlooms**: category buttons, product cards (image, name, description, price), cart with unit counts
- **Cart**: "Book your order" shows the review / pickup-preferred / delivery-with-charges message, then opens WhatsApp with the order filled in
- **Tuition Classes**: content from your poster plus the enrolment form (student name, parent's name, class, contact, board, school, subjects) with "Enroll now on WhatsApp"
- **Contact**: Alpana Singhal, 8750732668, WhatsApp link https://walink.me/0fz698, A502, Tower 1, River Heights, Rajnagar Extension, Ghaziabad

## Things to update (open index.html in a text editor)
1. **WhatsApp number for orders and enrolments**: find `const WA='918750732668'` near the top of the script. Use country code + number, no spaces or plus sign.
2. **Products and prices**: edit the `SHOPS` list. Each product is `['Name', price, old price (0 for none), 'Description', '🎁', 'Tag (Sale, New, Bestseller or empty)', 'photo link (optional)']`, e.g. `['Hardbound Diary',249,299,'Ruled pages.','📔','Sale','photos/diary.jpg']`.
3. **Phone number**: your poster shows 9873642668, your message gave 8750732668. The site uses 8750732668. Search and replace if needed.
4. **Saturday timing**: shown as 4pm to 6pm, as on the poster layout.

## Conversation summary
- Three verticals requested: Gift & Stationery, Handlooms (card-based shops with a cart), Tuition Classes (poster content and enrolment form).
- Shop orders and tuition enrolments both go to WhatsApp with details prefilled.
- Contact section with name, number, WhatsApp link and address.
- Latest update: the category filter now stays selected after adding an item to the cart.

## Version 2 changes (redesign inspired by gappa.co.in)
- Bright, playful light theme (no dark mode), new fonts and colours
- Scrolling announcement bar, sticky header with search, wishlist and cart
- Modern product cards: tags, sale price with % off, wishlist heart, add-to-cart that becomes a quantity counter
- Category filters and sort (price low to high or high to low) in both shops
- Slide-in cart drawer with the review / pickup / delivery message before WhatsApp
- Mobile bottom navigation bar, "Fresh picks" slider on Home, redesigned Tuition and Contact pages

## Favicon (version 2.1)
A pink rounded-square icon with a white "M" and a yellow sparkle. It is already embedded in index.html. Files for your own hosting: `favicon.svg`, `favicon.ico`, `apple-touch-icon.png` (phone home screen) and `favicon-512.png`. If you host the site yourself, you can also upload them next to index.html.

## Version 2.2 changes
- Compact footer (no phone or WhatsApp), clear borders on all cards and sections, drop-down arrows moved in from the edge and aligned

## Version 2.3 changes
- Footer now stays at the bottom of the screen on short pages such as the wishlist

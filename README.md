# Oriflame Seller Storefront: Greyscale Wireframe

A single-page, mobile-first wireframe of a seller storefront (example seller: "Mary's Edit"). Sellers share the page link on social media. It's built for **unmoderated usability testing**: open `index.html` in a browser, no build step needed.

## Page structure (conversion funnel)

| # | Module | Why it's placed here |
|---|--------|----------------------|
| 1 | Profile header + rating | Establishes trust (a real person, verified, 4.9★) within the first second of arriving from social |
| – | Sticky tabs: Shop · Advice · Join my team | Visitors can jump to their intent. Scroll position updates the active tab |
| 2 | Limited-time offer (3 for 2) | Urgency and value at the top converts impulse traffic |
| 3 | My Recommendation | Personal endorsement: the core reason to buy from a person, not a shop |
| 4 | Offers of the Month | Broadens the basket with catalogue deals |
| 5 | My Edit (filterable) | Browsing for visitors who haven't decided yet |
| 6 | Morning Routine bundle | Raises order value with a set price |
| 7 | Favourite of the Month | A second personal pick at the end of the browse |
| 8 | Customer reviews | Social proof that closes the shopping section |
| 9 | Skin Analysis | Guided discovery for undecided visitors, ends in a routine to buy |
| 10 | Virtual Try-On | Lowers risk for colour cosmetics |
| 11 | Posts & Tutorials (journal) | Magazine-style lead story + three columns |

| – | Ask Mary panel | AI adviser (instant answers) and live chat with Mary, opened from the top bar/dock |
| 14 | Meet My Team | Shows the team, a bridge to recruitment |
| 15 | Join My Team | Recruitment form (consent is opt-in) |
| 16 | Follow Me | Keeps visitors coming back |
| – | Sticky dock: Ask Mary · Bag | Primary actions always one tap away |

## Prototype behaviour
- Add to bag / Buy / Claim offer update the bag count and total. The bag sheet supports quantity changes. Checkout ends the prototype.
- My Edit filters and "Show all" work.
- Skin check runs selfie → 3 questions → results → routine to add to the bag.
- The try-on sheet has category and shade selection.
- The AI adviser gives canned, keyword-matched replies with hand-off to Mary.
- The join form validates and shows a success state. "How it works" explains the steps.
- Share uses the native share sheet, or copies the link.

## Responsive behaviour
- **Phone (< 700px):** single column, sticky section tabs, and a bottom dock with Ask Mary and Bag. Panels slide up from the bottom.
- **Tablet (700–1023px):** two-column grid. Wide modules (offer, recommendation, catalogue, My Edit, reviews, AI adviser, join form) span the full width.
- **Desktop (≥ 1024px):** 12-column editorial grid, with a split hero and a large portrait. Section navigation, Ask Mary and Bag sit in the top bar. Panels open as a right-hand drawer.

## Visual language
A warm tonal greyscale (stone neutrals, not pure grey), Inter throughout (light-weight accents in headings, tight tracking on display sizes), hairline borders, small corner radii, tracked uppercase labels, and one inverted (dark) card for live help.

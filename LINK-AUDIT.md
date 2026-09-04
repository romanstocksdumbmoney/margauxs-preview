# Margaux's preview — link audit

Verified against https://margauxsrestaurant.com/ (fetched 2026-09-04). Preview preserves real outbound destinations; internal pages are static redesign routes.

## Critical outbound (must work)

| Action | URL | Status |
|--------|-----|--------|
| OpenTable reserve | https://www.opentable.com/restaurant/profile/86053/reserve?rid=86053&restref=86053 | Preserved (home CTAs, nav, visit, footer) |
| Reservation request form | https://margauxsrestaurant.com/make-your-reservation/ | Preserved (links to live form) |
| Tonight's dinner menu page | https://margauxsrestaurant.com/margaux-menus/dinner-menu/ | Preserved |
| Live menu embed (iMenuPro) | https://imenupro.com/!wgj-1-z | Embedded on menus.html + linked |
| Phone | tel:9198469846 / displays (919) 846-9846 | Preserved |
| Google Maps directions | https://www.google.com/maps/dir//Margaux's+Restaurant,+8111+Creedmoor+Rd,+Raleigh,+NC+27613/@35.8978974,-78.7172102,13z/data=!3m1!5s0x89acf78a58f0b1d3:0x7edf0a3a84be2a95!4m9!4m8!1m0!1m5!1m1!1s0x89acf78ae7d5bb91:0xe212f3b358b9a8a1!2m2!1d-78.682105!2d35.897833!3e0 | Preserved (from live contact/footer) |
| Contact / Send Us a Message | https://margauxsrestaurant.com/contact/ | Preserved (live CF7 form) |
| Private party inquiry | https://margauxsrestaurant.com/private-parties/ | Preserved (live inquiry form) |
| Facebook | https://www.facebook.com/MargauxsRestaurant/ | Preserved |
| Instagram | https://www.instagram.com/margauxsrest/ | Preserved |
| X / Twitter | https://twitter.com/margauxsrest/ | Preserved |

## Secondary live-site deep links

| Label | URL |
|-------|-----|
| Our People (live) | https://margauxsrestaurant.com/our-people/ |
| Local Purveyors (live) | https://margauxsrestaurant.com/local-purveyors/ |
| Gallery | https://margauxsrestaurant.com/gallery/ |
| Testimonials | https://margauxsrestaurant.com/testimonials/ |
| Staff profiles | https://margauxsrestaurant.com/staff-member/{slug}/ |
| Specials page | https://margauxsrestaurant.com/margaux-menus/specials-menu/ |
| Live home | https://margauxsrestaurant.com/ |

## Not present on live site (intentionally not invented)

| Expected | Finding |
|----------|---------|
| Online order portal (Toast/ChowNow/etc.) | **None** — footer states “To Go Orders Available”; about copy says call / evening menu. Preview directs to-go to `tel:9198469846`. |
| Online gift-card checkout | **None** — gift certificates sold in any denomination by cash/card per house rules; no gift URL. |
| mailto: on public pages | **None found** in crawl. Pitch To: `margauxsrest@gmail.com` is for cold email only, not a fake site mailto. |
| Yelp US canonical | Live testimonials reference Yelp; one crawl hit was `yelp.ca` with `?start=40`. Preview does not deep-link a questionable Yelp URL; mentions Yelp in copy only. |

## Preview internal routes

- index.html, menus.html, about.html, private-parties.html, visit.html, people.html, purveyors.html
- Sticky banner names **margauxsrestaurant.com**

## Dated live site notes (pitch angle)

- ThemeForest **Total** theme (`wp-content/themes/Total`)
- Keyword-stuffed `<title>` (Fine Dining / Steakhouse / Seafood / Best Restaurants… stack)
- Divi/builder traces + heavy WPBakery / marketing overlays

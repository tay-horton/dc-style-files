# Module 12 — Accessibility Audit | DC Style Files

## Project
This ZIP updates the original **DC-Style-Files-Module-11-Restored-Original-Homepage** source, retaining its pages, original homepage artwork, typography, colors, descriptions, photo credits and image URLs. Files include `index.html`, `streetwear.html`, `vintage.html`, `css/home.css`, and `css/style.css`.

## Changes made in the source code
1. **Semantic HTML:** Retained original header, navigation, main, sections, articles and footer. Each page has one H1. Shop titles were changed from H2 to H3 beneath the H2 “Places to explore” for a clearer heading hierarchy.
2. **Alternative text:** Kept meaningful alt text for shop-themed reference photographs and the homepage poster. Updated the skateboard image description so it matches the subject rather than claiming the photo shows skaters in a park. The reference photographs are still clearly labeled as *not* actual store photographs.
3. **Understandable links:** Replaced generic repeated “Store website” text with links naming each shop. Clarified homepage and next-page calls to action. The decorative arrow glyphs have `aria-hidden` so they do not add noise to screen-reader link names.
4. **Contrast:** Preserved the existing high-contrast black, white, lime and cobalt design. Added a dark visible keyboard-focus outline, including on links over colored cards. Color is not the only cue that a link has focus.
5. **Keyboard:** Preserved skip-to-main-content links and logical DOM reading order, and strengthened focus indicator styling.
6. **Responsive:** Retained mobile CSS and added narrow-screen sizing rules for long headings and art details.
7. **Forms:** No forms exist on these three pages, so form-label testing is not applicable.

## Manual checks to complete before submission
These checks require your actual browser and cannot truthfully be marked passed by a source-code edit alone.

- [ ] Open **all three pages** and verify that original visual layout and all links/images display correctly. External images and linked websites require internet.
- [ ] Use **Tab**, **Shift+Tab**, and **Enter** from the start of each page. Check the skip link, page navigation, shop links and return links. On Safari for Mac, enable keyboard navigation through all controls if needed.
- [ ] Zoom to **200%** and narrow the browser window; verify nothing important overlaps, disappears, or requires excessive horizontal scrolling.
- [ ] Test representative text/background combinations with the **WebAIM Contrast Checker** (body copy, navigation, buttons, image credit text). Adjust if any combination fails applicable WCAG thresholds.
- [ ] Run each page through **WAVE** or **Lighthouse** from a hosted or locally served site, review any alerts, and address applicable errors. An automated check is not a substitute for reading-order/keyboard review.
- [ ] After making any further fixes, run the same manual and automated checks again.

## Sample reflection (edit to match your actual test results)
For my DC Style Files project, I reviewed the HTML, headings, images, links, and responsive styling on the Home, Streetwear & Sneakers, and Vintage & Boutiques pages. I kept my original design because I wanted the site to feel consistent with the earlier modules. I improved the heading hierarchy for the store listings, made repeated links more descriptive, adjusted an inaccurate image description, and strengthened keyboard focus styles. I also added narrow-screen adjustments. Next, I need to confirm these changes with keyboard, zoom, contrast, and automated browser tests so I can catch anything the code review missed.

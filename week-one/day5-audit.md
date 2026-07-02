Day 5: Chrome DevTools Analytics Audit
Core DevTools Panels
- Elements: Used to map out the HTML and CSS of a page. This is where we find CSS selectors to target specific user clicks (like buttons). We prioritize clean, unique class selectors (e.g., .single_add_to_cart_button) over fragile, auto-generated paths.

- Network: Acts as our radar for outgoing data. Filtering requests by collect verifies that GA4 is firing and sending data (like page_view). Filtering by gtm proves that Google Tag Manager is actively loading on the page.
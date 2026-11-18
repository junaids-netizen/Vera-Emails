# Vera Thanksgiving Email Device Preview

A single static page that previews the Thanksgiving Grocery Reward Boost email design at five screen widths (desktop, tablet, three phone sizes) and in three font states (brand fonts, Google fonts only, fonts blocked).

## What is in this folder

- `index.html`: the whole page. It is self-contained: the production email, its eight images, the design mockup, the logo and the Denton font files are embedded inside it. Outside requests go to Google Fonts (Geist, Fraunces) and to cdnjs for the JSZip library used by the zip export.

## Export panel

The page can export the production email for MoEngage: a zip of everything, the HTML alone, a plain-text version, each image, and copy buttons for the HTML, subject line and preheader. Paste the hosted image folder address first and the exported HTML will point at it.

## Deploying

This is a plain static site with no build step. Any static host works. On GitHub Pages, publish the branch root that contains `index.html`.

## Before making this public

- The email shown is an unapproved draft: dates are placeholders and the new copy has not been through compliance review.
- `index.html` embeds the Denton font files. Check that your Denton licence allows them to be served from a public page or stored in a public repository.
- This is a browser preview of screen widths and font fallback. It does not reproduce how Gmail, Outlook or Yahoo process email code.
- The page opens on the production email. The design mockup view (live fonts, coupon notches) is kept for comparison and is not what gets exported.

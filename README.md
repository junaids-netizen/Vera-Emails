# Vera Thanksgiving Email Device Preview

A single static page that previews the Thanksgiving Grocery Reward Boost email design at five screen widths (desktop, tablet, three phone sizes) and in three font states (brand fonts, Google fonts only, fonts blocked).

## What is in this folder

- `index.html`: the whole page. It is self-contained: the email markup, the logo and the Denton font files are embedded inside it. The only outside request is to Google Fonts for Geist and Fraunces.

## Deploying

This is a plain static site with no build step. Any static host works. On GitHub Pages, publish the branch root that contains `index.html`.

## Before making this public

- The email shown is an unapproved draft: dates are placeholders and the new copy has not been through compliance review.
- `index.html` embeds the Denton font files. Check that your Denton licence allows them to be served from a public page or stored in a public repository.
- This is a browser preview of screen widths and font fallback. It does not reproduce how Gmail, Outlook or Yahoo process email code.
- The preview shows the design mockup, not the production email build (which uses images for the Denton elements and has no coupon notches).

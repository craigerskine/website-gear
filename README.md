# [website-gear](https://craigerskine.github.io/website-gear/)
Simple cataloging site example.

* [DEMO](https://craigerskine.github.io/website-gear/)
* [Live Example](https://qrayg.com/rig/)

## Features

* Self contained (uses CDN for CSS and JS frameworks)
* Unlimited categories
* Unlimited hardware
* Customizable icons and colors
* Responsive layout (gracefully adjusts layout based on screen size)

## Instructions

1. Fork/Clone this repo
2. Edit the settings and make sure GitHub Pages is set to main/root 
    1. After you save this setting it will generate a hosted website that you can view on any internet enabled device
3. Edit the `index.html` page, specifically the vue data near the bottom of the page to add your own categories, hardware, etc. This uses a similar structure to [JSON](https://www.w3schools.com/js/js_json.asp)

Keep in mind that after you commit a change, it may take a few minutes for the hosted version to pull the update. This is normal and how GitHub pages work by default.

----

## Notes

* Use [Font Awesome v4](https://fontawesome.com/v4.7.0/icons/) icon names to replace icons... `fa-cogs`, `fa-battery`, etc.
* Use [Tailwind v2](https://tailwindcss.com/docs/customizing-colors) color names to adjust color schemes... `pink-500`, `yellow-200`, etc.
* To apply the preordered tag, use `soon: true` somewhere in the root hardware line item.
* There is a reserved `Obsolete` category keyword that uses a faded, strikethrough style.

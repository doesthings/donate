# donate

A one-page redirect: **https://doesthings.github.io/donate/** forwards to the current donation page.

Apps and READMEs link here instead of straight to Ko-fi, so the destination can change without
an app update. To change it, replace the URL everywhere in `index.html` (the `refresh` meta
tag, the `canonical` link, `TARGET` in the script and the fallback link) and push to `main`.
GitHub Pages updates within a minute or two.

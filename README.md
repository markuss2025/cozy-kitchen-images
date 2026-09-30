# cozy-kitchen-images

Image assets for https://cozykitchencoffee.blogspot.com/ , served through jsDelivr.

**Do not delete, rename or force-push over these files.** Live blog posts hotlink
them by commit SHA (`cdn.jsdelivr.net/gh/markuss2025/cozy-kitchen-images@<sha>/...`),
so a removed or renamed file is a broken image on a published page.

Why this exists: the first batch of images for newer posts was hosted on an
anonymous free image host that stopped serving 13 of 22 files (the TLS handshake
completed and no byte ever followed). Files here are served from a CDN and pinned
to an immutable commit.

Layout: one folder per post slug, files numbered in page order.

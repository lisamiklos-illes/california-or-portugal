# California or Portugal? 🌅

A cute little speed-guessing game. A photo flashes for **5 seconds** — guess whether it
was taken in **California** or **Portugal**. Score as many as you can in **2 minutes**.

Photos are pulled live from [Wikimedia Commons](https://commons.wikimedia.org/) (free, no
API key) using matched themes — beaches, coastlines, cliffs, lighthouses, vineyards,
harbors, surf — so images from both places look genuinely similar.

## Play

It's a single self-contained `index.html` — no build step, no dependencies.

- **Online:** open the hosted link.
- **Locally:** just open `index.html` in a browser (needs an internet connection, since
  photos stream from Wikimedia).

Tap the buttons, or use **←** for California / **→** for Portugal.

## Hosting on Render

Deploy as a **Static Site**:

- **Build Command:** *(leave empty)*
- **Publish Directory:** `.`

Render will serve `index.html` at the root.

## Credits

- Photos: contributors to Wikimedia Commons.
- Built by [Lisa Miklos-Illes](https://lisamiklos-illes.com).

# Vairocana Studios website

The studio's website, served by GitHub Pages at https://ringsel.github.io.

| Path | What it is |
|---|---|
| `index.html` | The studio's home: its games and how to reach it |
| `emberheart/` | EmberHeart's page |
| `emberheart/privacy/` | EmberHeart's privacy policy. Its address, https://ringsel.github.io/emberheart/privacy/, goes in Google Play Console and in the game's `native/emberheart.config.json` (`privacyPolicyUrl`) |
| `app-ads.txt` | AdMob's list of who may sell the studio's ad space. It must stay at the top of the site |
| `404.html` | The page shown for an address that does not exist |
| `assets/` | One stylesheet, the pictures, and the Press Start 2P font (SIL Open Font License, its licence beside it) |

Everything is static: no build step, no scripts, no cookies and no analytics. A change pushed to `main` is live in a minute or two.

To add a game: copy one `<article class="card">` block in `index.html`, and give the game its own folder like `emberheart/` if it needs a page or a privacy policy of its own.

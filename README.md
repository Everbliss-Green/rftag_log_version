# RFTag Release Notes

Public changelog page for the RFTag app (iOS &amp; Android), hosted on GitHub Pages.

`index.html` is a single, self-contained file — inline CSS and inline SVG icons, no
external dependencies — so it works on GitHub Pages with zero build step.

## Preview locally

Open the file directly in a browser:

```sh
open index.html
```

## Enable GitHub Pages

1. Push this repo to GitHub.
2. Go to **Settings → Pages**.
3. Under **Build and deployment**, set **Source** to *Deploy from a branch*.
4. Choose branch **`main`** and folder **`/ (root)`**, then **Save**.
5. The page will be served at `https://<user>.github.io/<repo>/`.

## Updating for a new release

Edit `index.html`: bump the `.version-badge` text and release date in the hero, then
add or update the feature cards under the "What's new" section.

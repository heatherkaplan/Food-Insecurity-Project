# Good2Grow

Website for Good2Grow — a community project by Heather Kaplan teaching kids in
underserved Philadelphia neighborhoods to grow their own food.

## Contents

- `index.html` — the site (single page, all styles inline)
- `support.js` — small runtime the page uses for rendering and interactions
- `img/` — botanical illustrations and garden photos

## Running it locally

Open `index.html` in a browser, or serve the folder:

```
python3 -m http.server
```

then visit http://localhost:8000

## Publishing with GitHub Pages

1. Push the contents of this folder to the repository root on the `main` branch.
2. In the repository, go to **Settings → Pages**.
3. Under **Build and deployment**, set Source to **Deploy from a branch**,
   branch `main`, folder `/ (root)`, and save.
4. The site goes live at `https://<username>.github.io/<repo>/` in a minute or two.

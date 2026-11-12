# HKU Course Weaver - public project page

A single static page that documents the project. It is published with GitHub Pages
from the root of this repository; there is no build step and no external asset: open
`index.html` and it renders.

## Publish

1. Repository **Settings -> Pages**.
2. Source: *Deploy from a branch*, branch `main`, folder `/ (root)`.
3. The page appears at `https://<account>.github.io/<repository>/` after a minute.

## Update

Edit `index.html` / `styles.css` and push to `main`. Nothing else is needed.

## What must not end up here

- member names, student numbers, email addresses;
- API keys, `.env` files, screenshots of a terminal that shows either;
- course records or datasets - the data lives in the private project repository, together
  with its provenance manifest. This page only describes it.

The working system is a local Java service (`courseweaver-server`). This page is
documentation, not a hosted copy of the app, and it must not imply otherwise.

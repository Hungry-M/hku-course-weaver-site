# HKU Course Weaver - public project page

A single static Portal-style page that documents the project. It is published with
GitHub Pages from the root of this repository; there is no build step and no runtime
dependency. All images and styles are local, so opening `index.html` renders the page.

The page follows the product's own HKU Portal-inspired frame: white top bar, pale
workspace, side navigation, flat white cards, dark-green notice and green tiles. It
reuses the project's About-the-project structure instead of maintaining a separate
landing-page design.

## Publish

1. Repository **Settings -> Pages**.
2. Source: *Deploy from a branch*, branch `main`, folder `/ (root)`.
3. The page appears at `https://<account>.github.io/<repository>/` after a minute.

## Update

Edit `index.html` / `styles.css` and push to `main`. Nothing else is needed.

Local preview assets:

- `assets/hku-course-weaver-logo.png` - project wordmark
- `assets/course-info-preview.png` - current English Course Info view
- `assets/plan-preview.png` - current English My Plan view
- `assets/pipeline.svg` - bounded pipeline diagram

## What must not end up here

- member names, student numbers, email addresses;
- API keys, `.env` files, screenshots of a terminal that shows either;
- course records or datasets - the data lives in the private project repository, together
  with its provenance manifest. This page only describes it.

The working system is a local Java service (`courseweaver-server`). This page is
documentation, not a hosted copy of the app, and it must not imply otherwise.

# Soak test 3 - source watching

A small static website ("My Small Site") with a home page, an about page and a single shared CSS stylesheet. No build step or server is required: open `index.html` in a browser.

## Pages

- `index.html` — home page with a welcome message and navigation.
- `about.html` — short about page.

Both pages link each other through the `Home` / `About` navigation.

## Stylesheet

`styles.css` holds the site's styles. Each page links it from its `<head>`:

```html
<link rel="stylesheet" href="styles.css">
```

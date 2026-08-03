# Event

A responsive, folder-powered event image gallery built with Jekyll and ready for GitHub Pages.

## Add photographs

Store images using this structure:

```text
IMAGES/<event>/<album>/<image>
```

For example:

```text
IMAGES/College_Fest/Opening_Ceremony/welcome.jpg
```

Commit and push the new files. The site discovers supported images automatically, so there is no gallery list to maintain. It supports JPG, JPEG, PNG, GIF, WebP, AVIF, and SVG files. Images placed deeper than the album level are intentionally ignored.

## Preview locally

```sh
bundle install
bundle exec jekyll serve
```

Then open `http://127.0.0.1:4000/Event/`.


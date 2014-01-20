# Reveal.js

Presentations are created using Reveal.js, see [the documentation here](https://github.com/hakimel/reveal.js).

## Give a Presentation

Clone this repository, and launch a presentation in your browser. For full effect make sure that you're viewing it via a webserver and not just file:///.

http://localhost/ctw-slides.html

## Differences from Standard Reveal.js

We've got our own theme! Whee.

If using external markdown files for creating your slides please use the following.

    <section data-markdown="file.md" data-separator="^\n={4,}" data-vertical="^\n-{4,}" data-notes="^Note:"></section>

This will allow separation of slides using `======*` and `------*` which is easier to read than newlines. Something like the following should work in your markdown file.

    # Welcome

    ==============================
    # Top Level

    ----------------------
    Nested #1

    ----------------------
    Nested #2

    ==============================
    # Top Level #2

    ==============================
    # Top Level #3

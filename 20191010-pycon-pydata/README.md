# Presentation of skorch at Pycon/PyData Berlin 2019

## Opening

Just open the created `presentation.html` in your favorite browser
(tested on Firefox).

## Running

To compile from source, open and edit `presentation.org` and run
`org-export-dispatch` in Emacs (C-c C-e v v).

If emacs usage is not desired, edit `presentation.html` directly.

### Installation

* [org-re-reveal](https://gitlab.com/oer/org-re-reveal)
  Fork of [ox-reveal](https://github.com/yjwen/org-reveal)
  Installable via MELPA

* [reveal.js](https://github.com/hakimel/reveal.js)

To get reveal.js, there are two options:

1. Get it via CDN by setting the export directive (e.g. `#+REVEAL_ROOT:
   https://cdnjs.cloudflare.com/ajax/libs/reveal.js/3.8.0`).
2. Download
   [reveal.js](https://github.com/hakimel/reveal.js/releases/tag/3.8.0)
   and include it with the other files (current approach)

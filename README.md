# Temporal Databases: Theory and Postgres

These are the slides and my notes for a talk about temporal databases given at pdxpug 20 June 2024, Chicago 15 October 2024, and SeaGL 8 November 2024.
It follows a talk I gave there and at PGCon back in 2019, but with lots of updates.
[The slides are online](https://illuminatedcomputing.com/talks/temporal-data-theory-and-postgres/) (press `s` to see speaker notes).
You can also read [all the slides as a PDF](slides.pdf),

You can also watch a [recording of the Chicago talk](https://illuminatedcomputing.com/pages/temporal-data-theory-and-postgres/).

It is built on [reveal.js](https://github.com/hakimel/reveal.js/),
from [a big markdown file](slides.md).

## Development

You can run the slides locally by saying:

```
npm install
npm start
```

You can get a slideshow-able PDF by going to http://localhost:8000/?print-pdf *in Chrome* and printing to a PDF. This is what you want to save as `slides.pdf`.

You can include speaker notes by going to http://localhost:8000/?print-pdf&showNotes=separate-page *in Chrome*, printing to a PDF, then printing the PDF. It uses a custom hack to get separate-page speaker notes with a white background. This is what you want to print before you give the talk.

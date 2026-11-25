# Year on the Shelf

A visual summary of your reading year from a Goodreads library export: a bookshelf of the year's spines illustrated by genre, stats, month by month, a reading calendar, highlights, ratings, authors, decades, your to-read pile and every book in a table. Click any book for its cover, description and details.

## Use it

Open the site and press **Load your CSV** (or drop the file on the page). It shows demo data until you do.

To get the file: on Goodreads go to **My Books → Import and export → Export library**.

Your file is read in the browser and never uploaded. The only network calls are to [Open Library](https://openlibrary.org) for each book's genre, cover and description (by ISBN, then title and author). Results are cached in your browser. If Open Library can't be reached, genres fall back to your Goodreads shelves. You can change any book's genre in the table, and that choice is remembered.

## Hosting

It's a single static `index.html`, served by GitHub Pages from the `main` branch.

# bookdown <img src='man/figures/logo.png' align="right" height="139" />


## Forked for kaisamng.github.io/RGuides

This was a fork of the original bookdown package specifically used to build the RGuides page I used for students. The only modification is allowing 4th level headings `####` to be displayed inside the table of contents in `bs4_book`.

To use:
1. Install this fork using devtools::install_github("kaisamng/bookdown")
2. Replace the `bs4_book.css` file in this root directoory with the one in the bookdown installed library files: run .libPaths() > bookdown > resources > bs4_book > bs4_book.css

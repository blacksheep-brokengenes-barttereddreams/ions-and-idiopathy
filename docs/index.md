--- 
title: "Ions, idiopathy, and institutional inertia"
author: "Kelli Feeser - BlackSheepBrokenGenesBartteredDreams"
date: "2025-01-02"
site: bookdown::bookdown_site
documentclass: book
# bibliography: [book.bib] # Remove `packages.bib` if it doesn't exist
description: |
  This book explores genomic and clinical analyses of Bartter Syndrome Type 3,
  providing insights into diagnosis, treatment, and institutional challenges.
link-citations: yes
github-repo: blacksheep-brokengenes-barttereddreams/ions-and-idiopathy
cover-image: images/cover.jpg # Ensure the file exists, or remove this line
url: https://blacksheep-brokengenes-barttereddreams.github.io/ions-and-idiopathy/
---



# Welcome

Welcome to the Bookdown site for the `ions-and-idiopathy` project. This project chronicles genomic and clinical analyses related to Bartter Syndrome Type 3.

## About

This book includes:
- Genomic analyses and workflows
- Clinical data summaries
- Tools used for diagnosis and treatment

## Usage 

Each **bookdown** chapter is an .Rmd file, and each .Rmd file can contain one (and only one) chapter. A chapter *must* start with a first-level heading: `# A good chapter`, and can contain one (and only one) first-level heading.

Use second-level and higher headings within chapters like: `## A short section` or `### An even shorter section`.

The `index.Rmd` file is required, and is also your first book chapter. It will be the homepage when you render the book.

## Render book

You can render the HTML version of this example book without changing anything:

1. Find the **Build** pane in the RStudio IDE, and

1. Click on **Build Book**, then select your output format, or select "All formats" if you'd like to use multiple formats from the same book source files.

Or build the book from the R console:


``` r
bookdown::render_book("index.Rmd", "bookdown::gitbook")

bookdown::render_book()
```

To render this example to PDF as a `bookdown::pdf_book`, you'll need to install XeLaTeX. You are recommended to install TinyTeX (which includes XeLaTeX): <https://yihui.org/tinytex/>.

## Preview book

As you work, you may start a local server to live preview this HTML book. This preview will update as you edit the book when you save individual .Rmd files. You can start the server in a work session by using the RStudio add-in "Preview book", or from the R console:


``` r
bookdown::serve_book()
```




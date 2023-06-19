# Hhu_thesis Format

## Installing

```bash
quarto use template schochastics/hhu_thesis
```

This will install the extension and create an example qmd file that you can use as a starting place for your article.

## Using

This is a custom format for a pdf document which should probably be rather a
template for a book, given that it uses the documentclass scrbook.

if you want to give this template a try, I would recommend the following
workflow:
In your main document, have a structure like this:

```md
\chapter{Introduction}
{{< include _introduction.qmd >}}

\chapter{Preliminaries}
{{< include _preliminaries.qmd >}}
```

and write the respective chapter content into the files `_introduction.qmd` and `_preliminaries.qmd`
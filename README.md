# Pathfinder Fate Accelerated Amalgamated

This humble, esoteric project compiles (most of) the content from Ed "Killer Shrike" Hastings' excellent [Pathfinder Fate Accelerated](http://www.killershrike.com/Fate/Fae/Pathfinder/Menu.aspx) RPG rules into a single, minimally-formatted document.

The document is provided in two formats:

-   **A Markdown text file**: This file can be used on its own or as the source for processing into other formats.
-   **A standalone HTML file**: This file provides simple visual formatting and a rudimentary slide-out navigation interface.

## How to use it

If you are not familiar with git repositories, do the following:

-  Click the "Clone or Download" button and select "Download Zip"
-  Save the zip archive to a local directory.
-  Unzip the archive.
-  Open a file and enjoy.

## Alterations and omissions

These files are not meant to be complete compilation of the [Pathfinder Fate Accelerated website](http://www.killershrike.com/Fate/Fae/Pathfinder/Menu.aspx).

-   The content in these files was pulled from the original website in early March 2018. Any changes made to the original website since March 2018 are not reflected in this document.
-   Some content was deliberately excluded from this compilation because it was not necessary to my idiosyncratic needs. In most cases you can find links to the excluded content in the "Online Content" section.

In some cases, minor edits have been made to the compiled content to be more appropriate for single-document use. Throughout the compiled content are cosmetic and formatting alterations made to suit my idiosyncratic needs and tastes. That said, the primary goal for this iteration was to apply a very light touch.

## Processing with Pandoc

The `templates` directory contains the [Pandoc](http://pandoc.org/) template used to convert the Markdown file into the HTML file. Try it at home with the following command:

```
pandoc -t html5 -f markdown_mmd+pipe_tables+fenced_divs+yaml_metadata_block --data-dir=. --template=pfaea.html5 --toc Pathfinder-FAE-Amalgamated.md -o Pathfinder-FAE-Amalgamated.html
```

## Acknowledgments

Aside for the minor alterations noted above, the text content of these files is the work of Ed "Killer Shrike" Hastings; all rights of authorship belong to him. His informal "license" in quite generous:

>  "(c) do whatever you want with it, but if you share it, credit me as Ed 
>  'Killer Shrike' Hastings for the original work and if practical a link to
>  the hack's main page ( http://www.killershrike.com/Fate/Fae/Pathfinder/Menu.
>  aspx ) somewhere in the material."

All files in this specific repository are licensed under a [Creative Commons Attribution-NonCommercial 4.0 International License](https://creativecommons.org/licenses/by-nc-sa/4.0/). 






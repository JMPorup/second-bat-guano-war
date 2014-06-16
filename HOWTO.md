HOWTO
=====

Grab yourself a copy of the-second-bat-guano-war.html. This is the 
master file. Then download Calibre:

  http://calibre-ebook.com/download
  
Run:

    ebook-convert the-second-bat-guano-war.html the-second-bat-guano-war.epub \
    --cover the-second-bat-guano-war-cover.jpg \
    --author-sort "Porup, J.M." \
    --authors "J.M. Porup" \
    --language English \
    --title "The Second Bat Guano War" \
    --title-sort "Second Bat Guano War, The" \
    --preserve-cover-aspect-ratio
  
or if you're a Kindle user:

    ebook-convert the-second-bat-guano-war.html the-second-bat-guano-war.mobi \
    --cover the-second-bat-guano-war-cover.jpg \
    --author-sort "Porup, J.M." \
    --authors "J.M. Porup" \
    --language English \
    --title "The Second Bat Guano War" \
    --title-sort "Second Bat Guano War, The" \
    --prefer-author-sort

or if you just want a PDF:

    ebook-convert the-second-bat-guano-war.html the-second-bat-guano-war.pdf \
    --cover the-second-bat-guano-war-cover.jpg \
    --author-sort "Porup, J.M." \
    --authors "J.M. Porup" \
    --language English \
    --title "The Second Bat Guano War" \
    --title-sort "Second Bat Guano War, The" \
    --paper-size a4 \
    --pdf-add-toc \
    --pdf-page-numbers \
    --preserve-cover-aspect-ratio \
    --margin-bottom 72 \
    --margin-top 72 \
    --margin-left 72 \
    --margin-right 72

Calibre's full command-line interface is documented here:

  http://manual.calibre-ebook.com/cli/ebook-convert.html

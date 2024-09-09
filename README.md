At commit: 32976b2eb73385d773548e6efc9fb34e6c75b7f2 
`freeze: auto`, `type: website`

1. `quarto render`:

    ```
    [1/2] index.qmd
    Rendering qmd embeds
    [1/1] r.qmd


    processing file: r.qmd
    1/3           
    2/3 [addition]
    3/3           
    output file: r.knit.md

    [2/2] r.qmd


    processing file: r.qmd
    1/3           
    2/3 [addition]
    3/3           
    output file: r.knit.md


    Output created: _site/index.html
    ```

    Open `_site/index.html`. WORKS

2. `quarto render` again:

    ```
    [1/2] index.qmd
    [2/2] r.qmd

    Output created: _site/index.html
    ```

    Open `_site/index.html`. Links to "Source: R" don't work. `_site/r.embed-preview.html` is no longer present.


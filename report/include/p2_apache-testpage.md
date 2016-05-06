% Linux och små nätverk --- Laboration #5
% Jonas Sjöberg <tel12jsg@student.hig.se>

--------------------------------------------------------------------------------


Test av webbservern `apache` 
============================
Visas detta så vågar man väl påstå att det fungerar hjälpligt.


Skapandet av den här sidan
--------------------------
Den här sidan genererades på följande vis:

1. Skriv texten med markdown-syntax i en texteditor.

2. Omvandla markdown-filen till html med `pandoc`:  
    ```bash
    pandoc -f markdown -t html --smart --highlight-style=monochrome --standalone apache-testpage.md -o index.html
    ```

3. Kopiera `index.html` till `/var/www/html`



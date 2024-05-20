Het startbestand bevat een bibliotheek met nuttige afbeeldingen.

Klik op het 'Image gallery' pictogram.

![Een vierkant pictogram met een bergtafereel en de zon in het pictogram.](images/view-gallery.png)

Scroll door de afbeeldingsbibliotheek en noteer de bestandsnaam van een afbeelding die je wilt gebruiken op jouw webpagina.

![De afbeeldingsbibliotheek met het love.png-bestand getoond.](images/editorimage-gallery.png)

Voeg je afbeelding toe aan de `<main></main>` in `index.html` zodat deze op je webpagina verschijnt.

--- code ---
---
language: html
filename: index.html
line_numbers: true
line_number_start: 32
line_highlights: 35
---

    <!-- De hoofdinhoud van de webpagina staat tussen de tags main -->
    <main>
      Lorem ipsum dolor sit amet. 
      <img src="love.png" alt="Beschrijving van afbeeldingen.">
       
    </main>

--- /code ---
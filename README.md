# Joie store locator — kant-en-klaar pakket

Upload alle bestanden in deze map samen naar dezelfde GitHub Pages-map of webhostingmap. De belangrijkste bestanden zijn `index.html`, `index-fr.html`, `stores.json` en `Joie-Logo.webp`.

## Nederlandse en Franse landingspagina

`index.html` is de Nederlandse store locator. `index-fr.html` is de Franse store locator. De taalkeuze bovenaan navigeert tussen deze twee pagina’s. De footerlinks verwijzen automatisch naar de juiste taalversie van de info-, privacy-, cookie- en OpenStreetMap-pagina’s.

## Storedata uit spreadsheet

Gebruik `stores-spreadsheet-template.xlsx` of `stores-spreadsheet-template.csv` als basis voor de spreadsheet. Publiceer de spreadsheet vervolgens als JSON in dezelfde kolomstructuur, of exporteer naar `stores.json`. De website verwacht standaard het bestand `stores.json` in dezelfde map als de HTML-pagina’s.

Belangrijke kolommen zijn `website_nl` en `website_fr`. De Nederlandse pagina gebruikt `website_nl`; de Franse pagina gebruikt `website_fr`. Voor Google Maps gebruikt de website `place_id` wanneer beschikbaar, en anders `maps_query_nl` of `maps_query_fr`.

## Google Maps in juiste taal

De Nederlandse pagina voegt `hl=nl` toe aan de Google Maps-link. De Franse pagina voegt `hl=fr` toe aan de Google Maps-link.

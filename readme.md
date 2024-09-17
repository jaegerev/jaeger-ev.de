# Website des J.Ä.G.E.R e.V.

Die Website wird mit [Mobirise](https://forums.mobirise.com/discussion/25648/mobirise-v5-1-8-beta-for-debian-linux)
gestaltet und anschließend per git auf dieses repository gepusht.

Folgendes ist dabei zu beachten:

- Um Referenzen zu Mobirise in der fertigen Website (bspw. den Footer) zu entfernen, [hier](https://witsec.nl/extension-white-label.html) die *White Label* Extension herunterladen und in Mobirise importieren. Außerdem nutze ich die *Page Name* und *Language* Extensions, um die URLs der einzelnen Sites umzubenennen bzw. die Sprache der Website auf Deutsch festzulegen.
- Obwohl in den URLs nach wie vor `*.html` zu lesen ist, funktionieren die Links auch ohne diesen Suffix (siehe [hier](https://stackoverflow.com/questions/21244910/remove-html-extension-from-github-pages))
- Es gab ein Problem nach der Konvertierung der Bilder ins webp-Format, welches [hier](https://forums.mobirise.com/discussion/34197/project-crashed-after-restoring-all-assets-gone) erläutert wird. Kurzum: Nachdem die Website veröffentlicht wird, erstellt Mobirise den `image`-Ordner mit **webp**-Dateien, sucht beim Wieder-Import allerdings weiterhin nach Bildern im **jpg**-Format. Deshalb werden Bilder nun in beiden Formaten gespeichert und auf GitHub hochgeladen, damit scheint das Problem gelöst zu sein.

### Stilfragen

- Überschriften in *Title1 & bold*
- Textfelder gerne in *Title3 & normal*, sofern es gut auf die Seite passt, sonst *Text*
- **Chronik**: Abstand nach oben = 2, unten = 1; Größe der Fotos = (50)/70/200

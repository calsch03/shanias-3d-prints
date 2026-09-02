# Shania's 3D Prints

De website van Shania, die schattige beeldjes maakt met haar 3D-printer. Bezoekers zien haar laatste prints, haar TikTok, en kunnen een eigen beeldje aanvragen.

**Live:** https://calsch03.github.io/shanias-3d-prints/

Eén bestand, `index.html`, met alles erin. Geen framework, geen build-stap, geen server. Dubbelklikken werkt ook gewoon.

---

## Even opletten

De site staat nog vol **plaatshouders**: de beeldjes zijn getekend in plaats van gefotografeerd, de TikTok-naam `@shania` is verzonnen, en het aanvraagformulier staat in demo-modus — het controleert alles netjes, maar verstuurt nog niets.

Daarom staat er voorlopig een `noindex`-regel in `index.html` en een `robots.txt`, zodat Google de site nog niet oppikt. Haal die allebei weg zodra de echte inhoud erin staat.

## Iets aanpassen

De uitgebreide handleiding staat in `LEESMIJ.md` in de projectmap hierboven, buiten deze repository. Kort samengevat:

| Wat | Waar |
|---|---|
| TikTok-naam, video's, formuliersleutel | `const INSTELLINGEN` onderin `index.html` |
| Kleuren | `:root` bovenin `index.html` |
| De beeldjes in de galerij | de blokken `<button class="kaart">` |
| Foto's | zet ze in `afbeeldingen/`, zie `afbeeldingen/LEESMIJ.txt` |

## Wijziging online zetten

```
git add .
git commit -m "beschrijf kort wat je veranderd hebt"
git push
```

Ongeveer een minuut later staat het live. Kleine tekstwijzigingen kun je ook rechtstreeks op github.com doen: klik op `index.html`, dan op het potloodje.

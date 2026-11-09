# Elevator pitch

Ett kortspel för grupper där du pitchar dig själv. Varje kort har en bild och en fråga. Du **beskriver dig själv** enligt bilden, eller **berättar en situation** som matchar bilden. Valfri timer på 30 eller 60 sekunder gör det till en hissfärd.

Spelet är en variant av Icebreakers med samma kortmotor och samma 45 bilder, men med nya frågor: varje bild har två frågor, så det blir 90 kort.

Svenska och engelska. Språkknappen uppe till höger byter direkt.

## Spela

Öppna `index.html` i en webbläsare. Allt ligger i en enda fil utan byggsteg. Spelet hämtar bara typsnittet Figtree och Lilita One från Google Fonts. Utan nätverk används reservtypsnitt.

Funkar bra som GitHub Pages: sätt Pages till grenen `main`, mappen `/ (root)`.

## Flera telefoner

Välj antal spelare och skriv ett gemensamt ord på alla telefoner. Ordet avgör hur korten delas upp, så ingen får samma kort. Språket påverkar inte uppdelningen, så ni kan spela på olika språk.

Färdig länk per spelare, lägg till sist i adressen:

| Del | Betydelse |
| --- | --- |
| `kod-pizza` | gemensamt ord |
| `spelare-3` | antal spelare (2–4) |
| `plats-2` | den här spelarens position |
| `omgang-1` | omgång efter omblandning |
| `tva-kort` | två kort per drag |
| `eng` | engelska |

Exempel: `index.html#kod-pizza-spelare-3-plats-2-eng`

## English

A card game for groups where you pitch yourself. Each card shows a picture and a question. You either describe yourself as the picture, or tell a situation that fits it. An optional 30 or 60 second timer turns it into an elevator ride. The language button in the top right switches between Swedish and English. Open `index.html` in a browser to play.

## Licens

MIT, se [LICENSE](LICENSE).

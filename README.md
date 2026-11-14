# DOMU — Cheese from the heart of Sardinia

DOMU'S RECIPES is a small home-based selection of Sardinian cheese, honey and olive oil, based in Copenhagen.

## What's in this folder

- `index.html`: the home page. It has the nonna hero and 3 cheese cards; each card links to its own page. Images and font load from `assets/`.
- `pecorino-tenero.html`, `pecorino-semistagionato.html`, `pecorino-stagionato.html`: one page per cheese. Fresh is Monte Gonare, semi-aged is Su Furreddu, aged is San Platano. Each page has the product details and DOMU's pairings side by side, and a "Made by" link to the brand.
- `tasting-box.html`: the DOMU tasting box (the three cheeses + a 200 g jar of premium Sardinian organic honey), with "What's inside" and "How to taste it". Its images (`assets/tasting-box.jpg`, `assets/tasting-box-wide.jpg`) are earlier studio collages. They are not label photos of Monte Gonare, Su Furreddu or San Platano.
- `domu-cheeses-standalone.html`: the same page with everything embedded (base64), so it works offline as a single file.
- `assets/`
  - Cheese photos: `pecorino-tenero-3-mesi.jpg` (fresh card; studio photo), `semi-aged-studio.jpg` (Su Furreddu card; earlier studio photo), `san-platano.jpg` (aged, San Platano, photo by Formaggi Picciau)
  - San Platano spec sheets: `san-platano-spec-sheet.pdf` (English translation), `san-platano-scheda-tecnica-it.pdf` (Picciau's Italian original)
  - `hero-nonna.jpg`: the hero photo (AI-generated image)
  - `lockup-domus-recipes.png` / `.webp`: the "DOMU'S RECIPES" lettering with the sheep icon and subtitle, as on the poster
  - `sheep-icon.png`: the yellow sheep icon
  - `LondrinaSolid-Regular.ttf`: the heading font (Google Fonts, SIL Open Font License)
- `posters/`: the approved posters (`domu-nonna-home-1.jpg`, `domu-recipes-londrina.jpg`)
- `data/`: the cheese descriptions, line by line (`descriptions-en.json` in English, `descriptions-it.json` in Italian)

## Cheeses

| Our name | Product | Maker | Ageing on the site | Piece |
|---|---|---|---|---|
| Fresh | Monte Gonare | Cooperativa Agricola “Unione Pastori di Sarule”, Sarule (NU) | not stated | 250 g |
| Semi-aged | Su Furreddu | Caseus S.r.l., Thiesi (SS) | not stated | 250 g |
| Aged | San Platano | Formaggi Picciau, Decimomannu (CA) | at least 120 days | 250 g |

Su Furreddu is a mixed-milk cheese, not a sheep's-milk pecorino. Monte Gonare is a fresh sheep's-milk pecorino. San Platano is an aged sheep's-milk cheese.

## Credits

Monte Gonare is made by Cooperativa Agricola “Unione Pastori di Sarule” (https://www.caseificiosarule.it/i-pecorini/). Su Furreddu is made by Caseus S.r.l.; Caseus has no site of its own, so the brand link goes to its page on Kara Sardegna (https://www.karasardegna.it/marca.asp?id=60&ver=en).

San Platano is made by Formaggi Picciau in Decimomannu, Sardinia (https://www.picciauformaggi.it/formaggi-picciau/san-platano/). The photo and the Italian spec sheet are theirs. The English spec sheet is a translation of their product sheet (revision 00, 16/10/14); the figures in that PDF are unchanged. On the site, ingredients, ageing and storage follow Picciau's product page: sheep's milk, rennet, salt and native cultures; at least 120 days; storage at +8/10 °C.

No label crops of Monte Gonare or Su Furreddu were in the site files, so those two cards keep studio photographs. They are not pictures of the producers' labels.

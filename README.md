# Marko in Oli — Igrice 🎮

Zbirka domačih brskalniških igric. Statična stran (samo HTML/CSS/JS), gostuje na GitHub Pages.

**V živo:** https://tonijukic.github.io/markoinoligrice/

## Kako dodam novo igro

1. Ustvari mapo `igre/<ime-igre>/index.html` (samostojna HTML igra).
2. Dodaj sličico `slike/<ime-igre>.png` (razmerje ~16:10).
3. V `index.html` dodaj eno vrstico v seznam `GAMES`:

```js
{ slug:'ime-igre', title:'Ime igre', emoji:'🎲', img:'slike/ime-igre.png',
  desc:'Kratek opis igre.' },
```

To je vse. Commitaj in potisni — GitHub Pages samodejno objavi.

## Struktura

```
index.html          uvodni meni (podatkovno voden seznam iger)
igre/
  tankci/index.html      artilerijski dvoboj za 2 igralca
  dirkanje/index.html    3D dirka za 1–2 igralca
slike/                   sličice iger za meni
.nojekyll                Pages naj strežе datoteke kot so
```

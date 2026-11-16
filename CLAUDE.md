# CLAUDE.md — markoinoligrice (Marko in Oli — igrice)

> Per-project context. Loads automatically when working in this folder.
> **PERSONAL project — NOT F45, NOT a client.**

## What this is
Collection of homemade browser games. Static site (HTML/CSS/JS), hosted on GitHub Pages.
**Live:** https://tonijukic.github.io/markoinoligrice/ · Own repo (`.git` in folder).

## How to add a new game
1. Create `igre/<slug>/index.html` (self-contained HTML game).
2. Add thumbnail `slike/<slug>.png` (~16:10).
3. Add one line to the `GAMES` list in `index.html`:
   ```js
   { slug:'ime-igre', title:'Ime igre', emoji:'🎲', img:'slike/ime-igre.png', desc:'Kratek opis igre.' },
   ```
4. Commit + push — GitHub Pages publishes automatically.

## Notes
- Personal/family project. Memory: [[project_markoinoligrice]].

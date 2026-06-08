# môj blog ♡

Osobný blog / portfolio na prezentáciu školských projektov.

## Štruktúra

```
📁 blog/
├── index.html          ← landing page (o mne)
├── projekty.html       ← prehľad všetkých projektov
├── css/
│   └── style.css       ← celý dizajn
└── projects/
    ├── projekt-1.html  ← šablóna detailu projektu
    └── projekt-2.html  ← ...
```

## Ako pridať nový projekt

1. Skopíruj `projects/projekt-1.html` a premenuj
2. Vyplň obsah (nadpis, popis, nástroje, linky)
3. Pridaj kartu na `projekty.html` aj na `index.html`
4. Push na GitHub → automaticky sa deployuje

## GitHub Pages

1. Vytvor repozitár napr. `moje-meno.github.io`
2. Uploadni všetky súbory
3. Settings → Pages → Source: main / root
4. Blog bude na `https://moje-meno.github.io`

## Prispôsobenie

* **Meno / info** — uprav v `index.html` v sekcii `.hero-info`
* **Farby** — uprav CSS premenné v `css/style.css` v `:root`
* **Profilová fotka** — nahraď `.avatar-placeholder` za `<img class="avatar" src="...">`
* **Socials** — uprav linky v `.hero-socials`
* **Playlist** — uprav songy v `.playlist-songs`


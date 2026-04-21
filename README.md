# EmoFun.pl — Jet Ski Rental Landing

Jednostronicowy lendingpage-wizytówka firmy **EmoFun.pl** — wypożyczalni skuterów wodnych.

## Struktura

```
.
├── index.html          # Strona główna (PL)
├── assets/
│   ├── styles.css      # Morska paleta + responsywny układ
│   ├── script.js       # Bourger-menu, plynne pojawianie sekcji
│   ├── logo.svg        # Logo (placeholder — podmień na własne)
│   └── favicon.svg
└── .github/workflows/pages.yml   # Deploy na GitHub Pages
```

## Co trzeba uzupełnić przed publikacją

1. **Logo** — podmień `assets/logo.svg` i `assets/favicon.svg` na pliki z brandingu (z `EMOFUN/WEB`).
2. **Zdjęcia do galerii** — wgraj 6 plików do `assets/gallery/` i zastąp tła `.gallery-item` w `assets/styles.css` (`background-image: url(...)`).
3. **Treść "O nas" i oferta** — zastąp teksty-zaślepki finalną kopią z `EMOFUN/WEB`.
4. **Dane dwóch podmiotów prawnych** w stopce — wypełnij w `index.html` pola:
   - Nazwa spółki, adres, NIP, REGON, KRS (sekcja `.legal-entity`).

## Lokalnie

Otwórz `index.html` w przeglądarce albo uruchom prosty serwer:

```bash
python3 -m http.server 8080
```

## Deploy (GitHub Pages)

Workflow `.github/workflows/pages.yml` publikuje stronę automatycznie po pushu na `main` lub `claude/jet-ski-landing-page-9Zbtq`.

Pierwsze uruchomienie — jednorazowo w **Settings → Pages** repozytorium ustaw **Source: GitHub Actions**.

## Kontakt

- Email: info@EmoFun.pl
- Telefon: +48 692 756 362
- Instagram: [@EmoFun.pl](https://instagram.com/EmoFun.pl)
- Facebook: [@EmoFun.pl](https://facebook.com/EmoFun.pl)

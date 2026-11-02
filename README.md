# Skoczek

Gra platformowa w przeglądarce. Żabka przechodzi 10 krain: Polana, Gęsty las, Słoneczna plaża, Wzgórza o zmierzchu, Mgliste bagno, Zimowa kraina, Kryształowa jaskinia, Nocna twierdza, Wulkan i Podniebne wyspy. Każda kraina ma własną muzykę.

## Sterowanie

| Akcja | Klawiatura | Telefon |
|---|---|---|
| Bieg | ← → lub A D | ◀ ▶ |
| Skok (przytrzymaj = wyżej) | Spacja, ↑, W | SKOK |
| Zeskok z deski / platformy | ↓ lub S | ▼ |
| Pauza | P lub Esc | II |

## Pliki

```
index.html              cała gra
favicon.ico             ikona dla Windows (skróty, pasek zadań)
manifest.webmanifest    instalacja na ekranie głównym
sw.js                   tryb offline
icons/                  ikony aplikacji
.nojekyll               wyłącza przetwarzanie Jekyll na GitHub Pages
```

## Publikacja na GitHub Pages

1. Utwórz nowe repozytorium, np. `skoczek` (publiczne).
2. **Add file → Upload files** i przeciągnij całą zawartość tego folderu (razem z folderem `icons`).
3. **Settings → Pages → Branch: main, folder: / (root) → Save**.
4. Po minucie gra działa pod adresem `https://TWOJA-NAZWA.github.io/skoczek/`.

## Instalacja na telefonie

Otwórz adres gry w przeglądarce, a potem z menu wybierz **Dodaj do ekranu głównego** (lub **Zainstaluj aplikację**). Gra uruchomi się na pełnym ekranie i działa też bez internetu.

## Aktualizacja gry

Podmień `index.html`, a w `sw.js` podbij numer wersji (teraz `skoczek-v2`, następnym razem `skoczek-v3` itd.), żeby telefony pobrały nową wersję.

## Instalacja na komputerze (Windows)

Otwórz adres gry w Edge lub Chrome i kliknij ikonę **Zainstaluj** w pasku adresu (lub menu **⋯ → Aplikacje → Zainstaluj tę witrynę jako aplikację**). Gra dostanie własną ikonę w menu Start i na pasku zadań.

Nie zapisuj strony przez **Zapisz jako**: zapisana kopia nie widzi plików obok siebie i nie da się jej zainstalować.

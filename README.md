# Studio 21 — portfolio

Publiczna strona portfolio, ostylowana design systemem **21zmysłów**
(czcionka Space Grotesk, Signal Orange, kafle 21px).

🌐 **Live:** https://twentyonelab.github.io/studio21-portfolio/

Strona to **jeden samowystarczalny plik** `index.html` — zdjęcia i czcionki
są w nim osadzone, więc działa bez internetu i bez serwera.

## 🔍 Jak podejrzeć zmiany (lokalnie, za darmo, natychmiast)

Kliknij dwa razy w `index.html` — otworzy się w przeglądarce. To wszystko.
(Żaden serwer nie jest potrzebny, bo plik jest samowystarczalny.)

## 🚀 Jak opublikować zmiany

Po edycji `index.html`:

```bash
git add index.html
git commit -m "opis zmiany"
git push
```

GitHub Pages sam przebuduje stronę — zmiana jest live po ~1 minucie
pod adresem powyżej.

## 🌍 Własna domena (na później)

Gdy będziesz mieć domenę:
1. W panelu DNS rejestratora dodaj rekord **CNAME** (`www` → `twentyonelab.github.io`)
   lub rekordy **A** dla domeny głównej (`185.199.108–111.153`).
2. W GitHub → Settings → Pages → **Custom domain** wpisz swoją domenę.
3. GitHub wystawi darmowy certyfikat HTTPS.

## 📁 Struktura

| Plik         | Zawartość                                  |
| ------------ | ------------------------------------------ |
| `index.html` | cała strona (HTML + CSS + zdjęcia + fonty) |
| `README.md`  | ten plik                                   |

# Genius Square PWA

Staattinen PWA-versio Genius Square -yksinpelistä.

## Tiedostot

- `index.html` - pelin HTML, CSS ja JavaScript
- `manifest.webmanifest` - PWA-manifesti
- `sw.js` - offline-välimuistia hoitava service worker
- `icons/` - sovellusikonit

## Paikallinen testaus

Service worker vaatii HTTP-palvelimen. Avaa kansio paikallisella palvelimella, esimerkiksi:

```powershell
python -m http.server 8080
```

Sen jälkeen avaa `http://localhost:8080/`.

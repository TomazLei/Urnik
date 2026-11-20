# Urnik Impol — spletna aplikacija (iPhone)

Urnik izmen (1.–4. izmena) za november 2026 – december 2027. Ista aplikacija kot Android
verzija, kot spletna aplikacija, ki jo na iPhone namestiš z začetnega zaslona.
Deluje tudi brez interneta; dopust, bolniška in opombe ostanejo samo na tvojem telefonu.

## Namestitev na iPhone
1. Odpri povezavo do aplikacije v **Safariju** (ne v Chromu).
2. Tapni **Deli** (kvadrat s puščico) → **Dodaj na začetni zaslon** → **Dodaj**.
3. Odpri **Urnik** z začetnega zaslona.

Na Androidu: odpri povezavo v Chromu → meni ⋮ → **Namesti aplikacijo** (ali uporabi APK).

## Objava (GitHub Pages)
Settings → Pages → *Build and deployment*: **Deploy from a branch**, branch **main**, folder **/ (root)** → Save.
Naslov aplikacije: `https://tomazlei.github.io/Urnik/`
(GitHub Pages pri brezplačnem računu deluje samo za **javne** repozitorije.)

## Posodobitev
Ta repozitorij vsebuje samo zgrajeno spletno aplikacijo. Izvorna koda je v projektu
`Urnik-Impol` (`src/App.jsx`). Nova verzija:

```
npm run build:web          # v mapi Urnik-Impol → dist-web/
```

Vsebino `dist-web/` skopiraj sem (README.md in .nojekyll pusti), commit in push.
Telefoni dobijo novo verzijo, ko naslednjič odprejo aplikacijo.

---

**English:** Shift calendar web app for iPhone. Open the link in Safari → Share → Add to Home
Screen. Hosted with GitHub Pages from `main` / root (repo must be public on a free plan).
Built from the `Urnik-Impol` project with `npm run build:web`.

# PROJECT STATE — Kurtán Károly · Tetőfedés

## Current goal
Prémium, filmszerű, conversion-focused one-page site — a vizuális polish kör UTÁN.

## Client facts (VERIFIED — only these may be used)
- Kurtán Károly
- Szolgáltatások: tetőfedés, tetőfelújítás, kéményjavítás, bádogozás (+ palatető, ácsmunka)
- Hajdúsámson és környéke (Debrecen megemlítve)
- 20+ év szakmai tapasztalat (NEM alapítási év — tilos konkrét évszám)
- Tel: 06 70 284 7949 (tel:+36702847949)
- E-mail: kurtan.karoly@gmail.com

## Honest content rules
- Fotók = „Illusztráció" jelöléssel, onerror fallbackkel; idézet + 5.0 értékelés explicit „bemutató" jelöléssel.
- Nincs kitalált referencia, évszám, hitelesített vélemény.

## Stack
- Egyetlen self-contained `index.html` (inline CSS + JS, Google Fonts CDN, Unsplash CDN).
- Fontok: Archivo Black (display — teljes magyar Ő/Ű), Archivo, IBM Plex Mono.

## Status — polish kör lezárva (v=22)
- [x] 16 kép réz-duotone márkakezelése (`.duo`) — megszűnt a vegyes stock-look
- [x] Hero: moody tetős fotó (photo-1518780664697), erősebb rétegzett scrim
- [x] Kártya-overlay sötétítés (0.38/0.55/0.92) + réz-párna; mobil kártyatípus skála
- [x] scroll-margin-top:78px minden horgonynál; hover:none detail-láthatóság
- [x] Decades háttér duotone-deszaturálás
- [x] Korábbi körök: Archivo Black glifajavítás, tline ékezet-clip, chain fill:none, hotspotok, slider try/catch, elgépelések

## Open tasks / next best action
- Ügyfélfotók beillesztése (hero, referenciák, before/after párok) → jelölések eltávolítása.
- Opcionális: Formspree a form mögé, deploy csomag, többoldalas bővítés, SEO adalékok.

## Blockers
- App screenshot-tool átmenetileg „no frames" (webview kompozitálás) — a DOM/CSS-ellenőrzések PASS; a Preview fülön élőben nézhető.

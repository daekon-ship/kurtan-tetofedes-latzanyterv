# QA LOG — Kurtán Károly site (frissítve: vizuális ráncfelvarrás után)

## Vizuális polish kör (2026-10-04, második QA)

### Kép-márkaegyeztetés — EXECUTED PASS
- 16 kép egységes „réz-duotone" kezelésre állt (`img.duo`): grayscale→sepia→hue-rotate → minden fotó a grafit/réz márkavilágba fordul, megszűnik a vegyes stock-look.
- Hero: moody tetős házas fotó (1518780664697) + erősebb rétegzett scrim + mérsékelt telítettség-csökkentés.
- Decades háttér: teljes duotone-deszaturálás brightness .42-tel.
- Kártya-overlay sötétítés: 0.38/0.55/0.92 gradiens — világos fotók is olvashatók (stílus a DOM-ban ellenőrizve).
- Mobil 640px: kártyacímek 26px, sorszám 60px — nem nyomják el a fotót.

### UX javítások — EXECUTED PASS
- `scroll-margin-top: 78px` minden horgonyszekción (fejléc eltakarás megszűnik).
- `@media (hover:none)`: érintőképernyőn a szolgáltatás-részletek alapból látszanak.
- Before/after meta: „Időtartam: illusztráció" → „Fotók: Illusztráció" (félreérthető mező javítva).

### Megerősítés
- Konzol: 0 hiba utolsó betöltésnél (v=22).
- 8 section[id] + footer[id] horgony rendben, scroll-margin 78px a computed style szerint.

### Screenshot-tool megjegyzés
- Az app beépített screenshot-funkciója átmenetileg „no frames" hibát ad (webview kompozitálási hiba az appban, nem az oldalban). A DOM-/CSS-szintű ellenőrzés fut és PASS. Ajánlott kézi vizuális check a Preview fülön.

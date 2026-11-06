# Aktuális állapot: kiválasztott 1. koncepció

Az index.html már a kiválasztott, módosított főoldal. A portfóliómunkák egyelőre nem jelennek meg. A korábbi választó a koncepciok.html munkaanyagban található. Részletes döntések: .webprojekt/kivalasztott-design.md.

# Péntek László – három portfóliókoncepció

## Megnyitás
Nyisd meg az index.html fájlt böngészőben (dupla kattintás). Innen mindhárom teljes kezdőoldal elérhető:
- Karakteres kézjegy: sötét, tipográfiára építő megjelenés.
- Személyesen Lászlóval: világos, mélyzöld, portrés megjelenés.
- Nyitott műhely: kobaltkék, projektekre építő megjelenés.

Opcionális helyi szerver PowerShellben:
```powershell
Set-Location -LiteralPath 'D:\ai\Péntek László'
python -m http.server 8766 --bind 127.0.0.1
```
Ezután: http://127.0.0.1:8766/ . Leállítás: Ctrl+C.

## Tartalom és képek
A három koncepcio-*.html fájl önálló: saját stílusait és interakcióit is tartalmazza. A szövegek közvetlenül a HTML-ben szerkeszthetők. Projekt hozzáadásához a munkák szakasz egyik article elemét másold; egyedi cím, leírás, státusz és kép szükséges. Ne állítsunk igazolatlan ügyfélkapcsolatot vagy eredményt.

Az images/ tartalmazza a webes SVG-logót, optimalizált WebP-portrékat, a Keller Kata és Eliza oldalak tényleges képernyőképeit, illetve az előnézeti képeket. Fotócserénél a megfelelő HTML img elem src és alt mezőjét módosítsd. Az assets/ az eredeti alapanyagokat őrzi; azok változatlanok maradtak.

A kapcsolat e-mail-hivatkozással működik, a látogató levelezőjét nyitja meg. Nincs adatküldést színlelő űrlap. A LinkedIn-cím a felhasználó által megerősített profilra mutat.

## Technika és ellenőrzés
Statikus HTML-prototípusok, nincs npm vagy build lépés. Google Fonts és Tailwind Play CDN internetet használ; a teljes saját CSS és rendszerfont-tartalék miatt hálózat nélkül is használható az elrendezés. Ez a három vizuális irány összehasonlítására készült, nem a végleges React alkalmazás.

A 2026-11-06-i böngészős ellenőrzés során az index és mindhárom oldal 1440, 768, 375 és 320 px szélességen megfelelt: nincs vízszintes túlcsordulás, hiányzó kép, hibás belső hivatkozás vagy JavaScript-hiba. A három mobilmenü megnyitása és Escape bezárása, valamint a hat lenyitható projektleírás működése ellenőrzött. Asztali és mobil képernyőképek vizuálisan átnézve. Ez nem teljes akadálymentességi audit.

Részletes gépi eredmény: .webprojekt/qa-report.json.

## Továbblépés és publikálás
A következő lépés a kedvenc irány és részletek kiválasztása. Ebből épül a végleges weboldal és a designrendszer, a briefben javasolt React/TypeScript/Vite technológiával.
Most nincs automatikus publikálás vagy távoli Git-repo. Az élesítés külön feladat: a kiválasztott végleges változat optimalizálása, metaadatok, noindex eltávolítása, domain és GitHub Pages beállítása. A jelenlegi index.html egy belső koncepcióválasztó, nem a végleges portfólió kezdőoldala.

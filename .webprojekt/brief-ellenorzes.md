# Briefellenőrzés és projektindítás

Dátum: 2026-11-05. Kiegészítő ellenőrzési jegyzet. A brief kapcsolati e-mail-címe a felhasználó megerősítése alapján frissítve.

## Értékelés
A brief tervezésre alkalmas: világos a célközönség, a személyes márka, a hangnem, a szolgáltatások és a vizuális kiindulópont. A végleges portfólió tartalmi elkészítéséhez még szükséges néhány adat.

## Tisztázandó tartalom
- Bemutatható munkák: a mappában csak logó és portrék vannak. A két említett projekt lehetőség, nem igazolt referencia. Projektenként cím, státusz (tanulmány/ügyfélmunka), saját feladat, leírás és képek szükségesek. Addig ne legyen kitalált projekt vagy üres projektlink. A Munkáim elsődleges CTA csak valódi tartalommal hasznos.
- Kapcsolat – tisztázva (2026-11-05): a felhasználó megerősítette a pentek.laszlo1994@gmail.com használatát. Űrlap csak valódi feldolgozással és ellenőrzött kézbesítéssel kerüljön be.
- LinkedIn – tisztázva (2026-11-05): a felhasználó a https://www.linkedin.com/in/lászló-péntek/ címet erősítette meg. A briefben már ez szerepel; az új oldal ezt használja.
- Oldalszerkezet: a brief oldalakat és szekciókat is említ. Javaslat: első körben egy hosszú kezdőoldal horgonylinkekkel, később külön projektadatlapok. Ez javaslat, nem jóváhagyott döntés.
- AI szolgáltatás: a megfogalmazás maradjon feltérképezés és kísérletezés; konkrét, vállalható eredmény később tisztázandó.

## Alapanyagok
- assets/brand/logo/pl logo.svg: valódi vektor, 1000×1000 viewBox, P és L path elemek. Elsődleges webes forrásnak javasolt; a forma változatlan maradjon. Világos változat külön származtatott fájlban készíthető.
- pl logo.png: 4167×4167, 149744 bájt. Vizuálisan ellenőrzött fekete PL-monogram.
- portrait-working.jpg.jpg: 2000×1333, 1448858 bájt; vizuálisan ellenőrzött laptopos portré, bemutatkozáshoz alkalmas.
- portrait-standing.jpg.jpg: 1333×2000, 1812375 bájt.
- profile-small.jpg.jpg: 400×400, 38676 bájt.
- old-tech-banner.jpg.jpg: 1400×349, 72461 bájt; opcionális.
- A dupla .jpg.jpg kiterjesztés nem akadály. Az eredetiket megőrizzük; a webes másolatok kapjanak egyszerű neveket, reszponzív méreteket és WebP formátumot.

## Meglévő projekt vizsgálata
Forrás: https://github.com/LaszloPentek/LaszloPentek.github.io és a main ág nyers index.html fájlja, lekérve 2026-11-05.
A meglévő projekt statikus HTML/CSS, nem React alkalmazás. A forrásban fejlesztői/álláskereső bemutatkozás, három coming soon/lorem ipsum projektkártya, üres CV-hivatkozás, duplikált contact azonosító és action="#" űrlap található. A régi e-mail-linkből hiányzik a mailto:. Ezeket nem érdemes átvenni. A főoldal élő renderelését a webes lekérés nem tette lehetővé; a megállapítások a repository forrására vonatkoznak.

## Technikai és design-előkészítés
A brief React + TypeScript + Vite iránya követhető. A generalas skill statikus HTML/Tailwind prototípusokat készít; ez külön tervezési fázis, a kiválasztott irány kerülhet később React alkalmazásba. A WordPress a kínált szolgáltatás, nem a portfólió kötelező motorja.
A grafit/törtfehér paletta és PL-monogram jó alap. A lime csak visszafogott kiemelés legyen, a portrék és a tipográfia adják a karaktert. Fontválasztásnál magyar ékezetek és helyi betűkészlet-kiszolgálás ellenőrzendő. Kis méretben favicon-olvashatóságot külön kell vizsgálni.
Javasolt későbbi ellenőrzések: build, billentyűzetes menü, látható fókusz, csökkentett mozgás, kontraszt, 320/375/768/1440 px nézetek, belső hivatkozások, képméretek, SEO-metaadatok.
A domain és GitHub Pages konfiguráció külön élesítési feladat. Automatikus publikálás nincs.

## Következő lépés
A referenciák tisztázása, majd designkoncepciók kidolgozása. A kapcsolati adatok megerősítve. Még nem készült alkalmazás vagy jóváhagyott designterv.

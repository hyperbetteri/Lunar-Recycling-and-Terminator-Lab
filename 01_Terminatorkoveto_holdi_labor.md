# Terminátorkövető holdi kutató- és újrahasznosító labor

**Koncepcióterv — javított, műszakilag átnézett változat**

Szerző: Almási Andor · Eredeti koncepció: 2025. február · Javított változat: 2026. október

> **Megjegyzés.** Az eredeti anyagok 2025 elején AI-motorok segítségével készültek. Ez a változat megtartja az alapötletet, de a fizikai és mérnöki állításokat ellenőrzött számításokkal javítja. Az elvégzett javítások listája: [04 – Javítási napló](04_Javitasi_naplo.md).

## 1. Az alapötlet

A Holdon egy nap (napkeltétől napkeltéig) körülbelül **29,5 földi nap**. Egy rögzített helyen álló bázis így nagyjából két hétig napfényben, majd két hétig sötétben van: nappal a felszín +120 °C körülire melegszik, éjjel −170 °C alá hűl.

A **terminátorvonal** a nappali és az éjszakai oldal határa. Ha egy mozgó labor ezt a vonalat követi, **soha nem kerül a kéthetes holdi éjszakába**, és nem kell elviselnie a nappali hőcsúcsot sem. Folyamatosan napfényt kap az energiához, miközben a közvetlen közelében mindig van árnyék és hideg, ami a hőelvezetéshez és a hideg technológiákhoz hasznos.

**Az ötlet lényege tehát:** ne a holdi éjszakát próbáljuk túlélni hatalmas akkumulátorokkal, hanem kerüljük el — vándoroljunk a nappal és az éjszaka határán.

## 2. Miért a pólusok közelében? — a kulcsszámítás

A terminátorvonal a Hold felszínén annál lassabban halad, minél közelebb vagyunk a pólushoz. A sebesség:

```
v(φ) = 2π · R_Hold · cos(φ) / T_szinodikus
R_Hold ≈ 1737 km,  T_szinodikus ≈ 29,53 nap ≈ 708,7 óra
```

| Szélesség (φ) | A terminátor sebessége | Egy teljes kör hossza |
|---|---|---|
| 0° (Egyenlítő) | ≈ 15,4 km/óra | ≈ 10 900 km |
| 80° | ≈ 2,7 km/óra | ≈ 1 900 km |
| 85° | ≈ 1,3 km/óra | ≈ 950 km |
| 88° | ≈ 0,5 km/óra | ≈ 380 km |
| 89° | ≈ 0,27 km/óra | ≈ 190 km |

**Ez a koncepció legerősebb érve.** Az Egyenlítőnél egy labornak folyamatosan ~15 km/órával kellene haladnia, ami egy nehéz, ipari létesítménynek irreális. A pólus közelében viszont — például a 88–89. szélességi körön — **gyalogtempónál is lassabb** mozgás elegendő, és a teljes kör csak néhány száz kilométer. Ez egy nehéz, lassan haladó platformmal is követhető.

Ráadásul a Hold tengelyferdesége mindössze kb. 1,5°, ezért a pólusok közelében a Nap mindig a horizont közelében jár. Egyes magaslatokon szinte folyamatos a megvilágítás („örök fény csúcsai”), a közeli kráterek mélyén pedig tartósan árnyékos, rendkívül hideg (kb. 25–40 K) területek vannak, amelyekben vízjég is lehet. A pólusvidék tehát egyszerre ad **energiát, hideget és vizet**.

## 3. Mozgatás: lebegő pálya vagy kerekes platform?

Az eredeti terv szupravezető mágneses lebegtetésű (maglev) pályát javasolt. Ez hosszú távú vízióként érdekes, de két korlátja van:

1. **A szupravezetők hőmérséklete.** A gyakorlatban használt magas hőmérsékletű szupravezetők (pl. YBCO) kritikus hőmérséklete kb. 92 K (−181 °C), üzemi hőmérséklete jellemzően 65–77 K. A −150 °C (123 K) ehhez **nem elég hideg**. Sugárzó hűtőfelületekkel és aktív kriohűtőkkel elérhető, de nem „magától” adódik.
2. **A pálya mérete.** Akár egy 190 km-es kör is hatalmas mennyiségű, a Földről felszállítandó vagy helyben gyártandó pályaanyagot igényel.

**Javasolt lépcsőzetes megoldás:**

| Fázis | Mozgatás | Indok |
|---|---|---|
| 1. | Kerekes vagy lánctalpas, lassú platform | A szükséges 0,3–1,3 km/óra sebesség kerekekkel könnyen elérhető, pálya nélkül. |
| 2. | Moduláris egységek láncolata | Több kisebb modul vándorol együtt; egy meghibásodott egység nem állítja le az egészet. |
| 3. | Helyben gyártott pálya, később lebegtetés | Ha a regolitból már gyárthatók építőelemek, a pálya fokozatosan kiépíthető. |

## 4. Energia és hő

- **Napelemek:** a pólus közelében a Nap alacsonyan áll, ezért **függőleges, forgatható napelemtáblák** kellenek, amelyek követik a Nap irányát. A terminátor követése miatt ezek gyakorlatilag folyamatosan termelnek.
- **Energiatárolás:** mivel a labor elkerüli a kéthetes éjszakát, csak rövid kiesésekre (domborzati árnyék, karbantartás) kell tárolás. Ehhez akkumulátorok elegendők. A szuperkondenzátorok csak rövid csúcsterhelésekre jók, hosszabb tárolásra kicsi az energiasűrűségük.
- **Hőelvezetés:** az árnyékos oldal felé fordított sugárzó hűtőfelületek a hideg égbolt felé adják le a hőt. Ez természetes előnye a helyszínnek.
- **Magas hőmérséklet:** légkör hiányában a **koncentrált napfény** (tükrök, Fresnel-lencsék) könnyen ezer fok fölötti hőmérsékletet ad. Ez alkalmas alumíniumolvasztásra (660 °C) és a regolit szinterezésére is. Ez a megoldás jóval hatékonyabb, mint a hőszivattyúk (lásd a javítási naplót).

## 5. Mit dolgozna fel a labor?

Az eredeti koncepció a Föld körüli pályán keringő űrszemét Holdra szállítását is felvetette. Őszinte mérnöki értékelés szerint ez **energetikailag nagyon drága**: egy tárgy alacsony Föld körüli pályáról a Hold felszínére juttatása nagyjából 5,5–6 km/s sebességváltoztatást igényel, ami közel annyi, mint egy teljes holdi küldetés.

Ezért a reális sorrend:

1. **A holdbázison keletkező hulladék** — csomagolóanyagok, textíliák, szerkezeti elemek. Pontosan ezt célozza a NASA LunaRecycle Challenge versenye (lásd a [02 – LunaRecycle koncepció](02_LunaRecycle_hulladekfeldolgozasi_koncepcio.md) dokumentumot).
2. **A Holdon már ott lévő ember alkotta eszközök** — régi leszállóegységek, becsapódott rakétafokozatok. A becslések szerint ezek összesen nagyjából 180–200 tonnát tesznek ki.
3. **Hosszú távon** a Hold körüli pályán lévő eszközök, és csak egészen hosszú távon a Föld körüli űrszemét.

## 6. Mesterséges intelligencia a rendszerben

A labor egyik célja, hogy nagyrészt autonóm legyen. Az MI szerepei:

- **Navigáció:** a terminátor és a domborzati árnyékok előrejelzése, útvonaltervezés.
- **Anyagazonosítás:** a beérkező hulladék válogatása (spektrális és optikai érzékelés).
- **Folyamatirányítás:** az őrlés, olvasztás és formázás vezérlése.
- **Erőforrás-gazdálkodás:** energia, hő és készletek beosztása.

Az emberi felügyelet minden döntési pontnál megmarad. A szerző több AI-motorral végzett validációs munkája éppen azt mutatja, hogy az MI-kimeneteket ellenőrizni kell, nem vakon végrehajtani.

## 7. Nyitott kérdések

- A pólusvidéki domborzat pontos árnyéktérképe a választott útvonalon.
- A holdpor elleni védelem a mozgó alkatrészeken (lásd 02, 6. fejezet).
- A platform tömege és a Földről szállítandó minimális kezdő felszerelés.
- A kommunikáció biztosítása a Föld felé a pólus közelében (közvetítő műhold szükséges lehet).

## 8. Összegzés

A terminátorkövető labor alapötlete **fizikailag megalapozott**, és a pólusok közelében **mérnökileg is reális**: ott a szükséges sebesség gyalogtempónál kisebb, a teljes útvonal néhány száz kilométer, a környezet pedig egyszerre ad napfényt, hideget és vízjeget. A javított koncepció kerekes, moduláris platformmal indul, a koncentrált napfényt használja magas hőmérsékletű feldolgozásra, és elsősorban a holdbázison keletkező hulladékot dolgozza fel.

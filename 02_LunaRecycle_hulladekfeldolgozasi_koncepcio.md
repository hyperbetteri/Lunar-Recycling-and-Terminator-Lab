**Language:** [Magyar](02_LunaRecycle_hulladekfeldolgozasi_koncepcio.md) | [English](02_LunaRecycle_hulladekfeldolgozasi_koncepcio.en.md)
# Holdi hulladékfeldolgozási koncepció a NASA LunaRecycle Challenge-hez

**Koncepcióterv — javított, műszakilag átnézett változat**

Szerző: Almási Andor · Eredeti anyagok: 2025. február–március · Javított változat: 2026. október

> **Háttér.** A NASA LunaRecycle Challenge (a Centennial Challenges program része) olyan megoldásokat keres, amelyek egy holdbázison keletkező szilárd hulladékot hasznos anyaggá vagy termékké alakítanak. Ez a dokumentum egy magyar csapat 2025-ös felkészülése során készült anyagok javított változata. Az anyagok **Dr. Páli Jenő** felkérésére készültek, aki a Lunar Team Hungary csapatot szervezte, regisztrálta és csapatvezetőként képviselte, a versenyfelhívást feldolgozta, és a feldolgozandó három hulladéktételt kiválasztotta. Az eredeti, AI-motorok segítségével megfogalmazott szövegekben több műszaki hiba volt; ezeket a [04 – Javítási napló](04_Javitasi_naplo.md) sorolja fel.

## A csapat és a jelentkezés

Forrás: Dr. Páli Jenő 2025. február–márciusi levelei.

- **Csapat:** Lunar Team Hungary. A csapatot Dr. Páli Jenő regisztrálta a NASA Centennial Challenges weboldalán (regisztrációs szám: #670), és csapatvezetőként (Team Leader) képviselte.
- **Magyar részvétel:** a NASA Centennial Challenges addigi 23 versenyén még nem indult magyar csapat (Dr. Páli Jenő tájékoztatása).
- **Lebonyolító:** a versenyt az Alabamai Egyetem (The University of Alabama) bonyolította. A részvételhez a csapatnak az egyetemmel 16 oldalas részvételi megállapodást (Phase 1 Team Agreement) kellett kötnie.
- **Hivatalos oldal:** [lunarecyclechallenge.ua.edu](https://lunarecyclechallenge.ua.edu/#project) · magyar nyelvű hír: [origo.hu](https://www.origo.hu/tudomany/2024/10/nasa-verseny-hold)
- **Határidő (1. fázis):** 2025. március 31. — a jelentkezés és a megoldási javaslat benyújtása.
- **Díjazás:** pénzdíjra csak amerikai állampolgárok és cégek jogosultak; nem amerikai csapatok is indulhatnak, de ők elismerést kaphatnak.
- **Részvételi feltételek:** minden csapattagnak egyénileg kellett regisztrálnia, személyazonosságát és állampolgárságát igazolva, a csapatnak pedig 5000 USD összegű biztosítást vagy pénzügyi fedezetet (Proof of Insurance / Proof of Funds) kellett igazolnia.
- **A kiírás feldolgozása:** Dr. Páli Jenő a 44 oldalas versenykiírást (Phase 1 Rules) végigolvasta, a lényeges részeket kiemelte, és a még nem tisztázott részvételi feltételekről megkereste a szervezőket.

## 1. A verseny keretei (a nyilvános kiírás alapján)

**A referenciaküldetés:** 8 fős legénység, 1 éves holdi tartózkodás. A kiírás 6 hulladékkategóriát és 17 hulladéktételt sorol fel, pontos anyagösszetétellel.

**Két környezet:**

| | Nyomás alatti lakómodul (belső) | Holdfelszín (külső) |
|---|---|---|
| Gravitáció | 1,625 m/s² | 1,625 m/s² |
| Légnyomás | 57,2 kPa | 0,3 nPa (gyakorlatilag vákuum) |
| Hőmérséklet | 18–27 °C | 50–250 K (kb. −223 °C és −23 °C között) |
| Légösszetétel | ~34% O₂, ~66% N₂ | — |
| Méretkorlát | 4 db EXPRESS-rack dupla szekrény (a Nemzetközi Űrállomás szabványos kísérleti szekrénye, egyenként kb. 48 × 42 × 24 cm) | nincs |

**Fontos szabályok:**

- a hulladék **nem égethető el**;
- kerülni kell a mérgező kibocsátást, a **PFAS-vegyületeket** (per- és polifluorozott anyagok) és a **mikroműanyagot**; ha mégis keletkeznek, ezt kötelező bejelenteni;
- a holdi **regolit** (a Hold felszínét borító laza kőzetpor és törmelék) bármilyen mennyiségben szabadon felhasználható (specifikáció: [LHS-1](https://sciences.ucf.edu/class/wp-content/uploads/sites/23/2019/02/Spec_LHS-1.pdf));
- az első fázisban külön nem kell a holdporral foglalkozni, de javaslatot kell tenni a **holdpor elleni védelemre**;
- az első fázisban beadott terv nem feltétele a második fázisnak (prototípus építése): ott más ötlettel, eljárással és hulladéktípussal is lehet indulni.

**Elvárt termékek (példák a kiírásból):** konyhai eszközök, törölközők, törlőkendők, nitril kesztyű, étel-, víz-, vegyianyag- és gáztárolók, használati és szerelési eszközök (kábelkötegelő, pántok, hevederek, csavarkulcsok, csavarok), valamint olyan mindennapi tárgyak, amelyeket költségmegtakarítás miatt amúgy nem vinnének fel az űrbe.

## 2. A kiválasztott három hulladéktétel

Dr. Páli Jenő a 6 hulladékkategória 17 tételéből hármat választott ki, a három nehézségi szintből egyet-egyet:

| Tétel | Mennyiség (1 év, 8 fő) | Nehézség | Anyag |
|---|---|---|---|
| **Zotek F30 habosított csomagolóanyag** | ~10 m³ / ~1000 kg | 3 (legnehezebb) | PVDF-hab (fluorpolimer); a gyártó szerint térhálósított, vagyis a molekulaláncai keresztkötésekkel össze vannak kapcsolva |
| **Alumínium szerkezeti elemek** | ~9 m³ / ~900 kg | 2 (közepes) | >90% alumínium |
| **Nitril kesztyű** | ~0,22 m³ / ~41 kg | 1 (legkönnyebb) | nitrilkaucsuk |

A kiírás által hivatkozott anyagjellemzők: [Zotek F (gyártói oldal)](https://www.zotefoams.com/product/zotek/zotek-f-lightweight-pvdf-foam/) · [nitril kesztyű biztonsági adatlap](https://www.medpride.com/media/MSDS-NITRILE-PF-EXAM-GLOVE-5050X.pdf)

## 3. Az alapelv: hideg előkészítés, napfényes hő

A Holdon két „ingyenes” erőforrás van, amelyet a Földön drága előállítani:

- **Hideg:** az árnyékos oldalon és éjjel a hőmérséklet 100 K (−173 °C) alá eshet. Ezen a hőmérsékleten a legtöbb műanyag és gumi **üvegszerűen rideggé válik**, és mechanikusan könnyen porrá őrölhető. Ezt hívják kriogén (mélyhideg) őrlésnek; a Földön ehhez folyékony nitrogén kell, a Holdon a természetes hideg is elég.
- **Koncentrált napfény:** légkör nélkül a tükrökkel vagy Fresnel-lencsékkel összegyűjtött napfény **ezer fok fölé** emelheti a hőmérsékletet. Ez fém olvasztására és a regolit szinterezésére is elegendő.

A [terminátorkövető labor](01_Terminatorkoveto_holdi_labor.md) mindkettőhöz folyamatos hozzáférést ad: az egyik oldalon napfény, a másikon árnyék.

## 4. Feldolgozási láncok

### 4.1. Zotek F30 (PVDF-hab) — mechanikai út, hőbontás nélkül

A PVDF fluorpolimer. **Hevítésre (kb. 350 °C fölött) hidrogén-fluoridot (HF) bocsát ki**, amely erősen mérgező és maró. A PVDF egyes nemzetközi definíciók szerint maga is PFAS-nak minősül. Ezért a javasolt út **nem bontja el kémiailag** az anyagot, hanem mechanikusan alakítja át:

1. **Kriogén őrlés** zárt őrlőben: a hideg miatt rideg habot apró szemcsékké őröljük.
2. **Kompozit készítése:** a PVDF-őrleményt holdi regolittal és kötőanyagként a hulladékból visszanyert polietilénnel (a kiírásban több tiszta polietilén hulladéktétel is szerepel, pl. buborékfólia és légpárna) keverjük.
3. **Melegsajtolás** mérsékelt hőmérsékleten (150–200 °C), jóval a PVDF bomlási hőmérséklete alatt.
4. **Termékek:** hőszigetelő lapok, burkolólapok, csőtartók, tálcák, távtartók.

**Bejelentendő kockázatok:** az őrlés mikroműanyag-port termel, ezért a folyamat zárt, porelszívós rendszerben fut, a por pedig teljes egészében a kompozitba kerül. Mivel az alapanyag fluorpolimer, a PFAS-tartalmat a pályázatban kötelező jelezni.

### 4.2. Alumínium — olvasztás napkemencében

1. Darabolás és tisztítás.
2. **Olvasztás** (660 °C) koncentrált napfénnyel működő kemencében, vagy indukciós kemencében, védőgázban vagy vákuumban.
3. **Termékek:** öntött alkatrészek (csavarkulcs, konzol, tartó), illetve huzal. A huzalból fém-3D-nyomtató (huzal-ív additív gyártás) tetszőleges alkatrészt tud készíteni: elektromos ívvel megolvasztja a huzalt, és rétegről rétegre építi fel a tárgyat.

A külső vákuum előny: az olvadék nem oxidálódik.

### 4.3. Nitril kesztyű — gumiőrlemény

1. Fertőtlenítés és kriogén őrlés gumiőrleménnyé.
2. Keverés kötőanyaggal, majd sajtolás.
3. **Termékek:** csúszásgátló alátétek, rezgéscsillapító betétek, tömítőgyűrűk.

## 5. Energia és hő — javított megoldás

| Feladat | Hőmérséklet | Javasolt forrás |
|---|---|---|
| Kriogén őrlés | 150 K (−123 °C) alatt | Árnyékoldali sugárzó hűtés |
| Polimer melegsajtolás | 150–200 °C | Elektromos fűtés napelemről, vagy kis koncentrálású napkollektor |
| Alumíniumolvasztás | ~700 °C | Koncentrált napfény (napkemence) |
| Regolit-szinterezés | ~1100 °C | Koncentrált napfény |

## 6. Védelem a holdpor ellen

A holdpor éles szemcséjű, elektrosztatikusan feltöltődik, és minden résbe bejut. Javasolt védelem:

- **Elektrodinamikus porvédő pajzs:** a felületbe ágyazott elektródák váltakozó feszültséggel lesöprik a port. A NASA ezt a technológiát már tesztelte.
- Zárt, labirinttömítéses csapágyak és mozgó alkatrészek.
- Zsilipkamra a hulladék bejuttatásához, porleválasztással.
- A belső feldolgozás a nyomás alatti modulban fut; kívül csak a napkemence és a hűtőfelületek vannak.

## 7. Mit nem állítunk

- Nem állítunk egzakt újrahasznosítási arányt. Az eredeti szövegekben szereplő 70–90%-os értékek becslések voltak, mérés nélkül.
- A feldolgozási láncok laboratóriumi kísérlettel még nincsenek igazolva. A következő lépés földi kísérlet lenne: PVDF-hab kriogén őrlése, majd regolitszimulánssal kevert kompozit sajtolása és szilárdsági vizsgálata.

## 8. Összegzés

A javított koncepció a Hold két természetes előnyére épít: a **hidegre**, amely az őrlést teszi egyszerűvé, és a **koncentrált napfényre**, amely a magas hőmérsékletű feldolgozást. A legnehezebb tétel, a PVDF-hab esetében szándékosan **kerüli a hőbontást**, így elkerüli a mérgező hidrogén-fluorid képződését, és illeszkedik a verseny PFAS- és kibocsátási szabályaihoz.

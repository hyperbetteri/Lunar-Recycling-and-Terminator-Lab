# Javítási napló

**Mi volt hibás a 2025-ös, AI-motorokkal megfogalmazott eredeti anyagokban, és hogyan javítottuk**

Az eredeti szövegek 2024 végén és 2025 elején készültek, több AI-motor segítségével. Az ötletek a szerzőtől származnak, a megfogalmazásban azonban a motorok több olyan állítást is beírtak, amely fizikailag vagy kémiailag hibás. Ez a napló a szerző validációs elvét követi: **a hibát nem elrejtjük, hanem dokumentáljuk és kijavítjuk.**

| # | Eredeti állítás | Mi a helyes | Hol javítottuk |
|---|---|---|---|
| 1 | A Hold terminátorvonala kb. **15 km/nap** sebességgel halad. | Az Egyenlítőnél kb. **15 km/óra** (≈ 370 km/nap). A pólusok felé arányosan lassul: a 89. szélességi körön kb. 0,27 km/óra. | 01, 2. fejezet |
| 2 | A terminátor éjszakai oldalának **−150 °C** alatti hőmérséklete fenntartja a szupravezetők működését. | A magas hőmérsékletű szupravezetőkhöz kb. 92 K (−181 °C) alatti, a gyakorlatban 65–77 K hőmérséklet kell. A −150 °C ehhez nem elég, sugárzó és aktív hűtés szükséges. | 01, 3. fejezet |
| 3 | A Föld körüli pályán keringő űrszemét a Holdra szállítható feldolgozásra. | Fizikailag lehetséges, de nagyon energiaigényes (~5,5–6 km/s sebességváltoztatás alacsony Föld körüli pályáról a holdfelszínig). A holdbázison keletkező hulladék és a Holdon már ott lévő eszközök a reális elsődleges célpontok. | 01, 5. fejezet |
| 4 | A szuperkondenzátorok tárolják az energiát. | Rövid csúcsterhelésre alkalmasak; hosszabb tárolásra kicsi az energiasűrűségük. A terminátorkövetés miatt hosszú tárolásra amúgy sincs szükség. | 01, 4. fejezet |
| 5 | Hőszivattyúkkal **3–4-szer hatékonyabb** energiafelhasználás érhető el a holdi hőmérséklet-különbségek kihasználásával. | Nagy hőmérséklet-különbségnél a hőszivattyú hatásfoka erősen romlik. Kb. 100 K-ről 443 K-re (170 °C) az elméleti maximum is csak kb. 1,3, a valóságban ennél kevesebb. A magas hőmérsékletre a koncentrált napfény a jó megoldás. | 02, 5. fejezet |
| 6 | A 170 °C-os hő **hőcserélőkkel** 400–500 °C-ra emelhető. | Hőcserélő nem tudja növelni a hőmérsékletet, csak hőt ad át a melegebbről a hidegebbre. Magasabb hőmérséklethez napkoncentrátor vagy elektromos fűtés kell. | 02, 5. fejezet |
| 7 | A műanyagok **pirolízissel** bonthatók gázra, olajra és szénre. | A verseny tiltja az égetést, és kéri a mérgező kibocsátás kerülését. A PVDF hevítéskor mérgező hidrogén-fluoridot ad. A javított koncepció a PVDF-et mechanikusan dolgozza fel, hőbontás nélkül. | 02, 4.1 |
| 8 | A Zotek F30 (PVDF) peroxidokkal „feloldható”, és LiPF₆-tal reagáltatva akkumulátor-elektrolit lesz belőle. | A peroxidok polimerizációs iniciátorok, nem bontják a szén–fluor kötést. A PVDF-et az akkumulátoriparban kötőanyagként és szeparátorként használják, nem így készül belőle elektrolit. Ezt az irányt elhagytuk. | 02, 4.1 |
| 9 | A Zotek F30 200 °C fölött megolvasztható és újraformázható. | A gyártó szerint a Zotek F térhálósított hab, ezért nem olvasztható vissza úgy, mint egy egyszerű hőre lágyuló műanyag. Őrleményként, töltőanyagként hasznosítható. | 02, 4.1 |
| 10 | Golyós őrléssel **nanométeres** szemcseméret érhető el. | Egy habosított polimernél ez nem reális, és nem is szükséges. A kompozithoz a néhány tized milliméteres őrlemény is megfelelő. | 02, 4.1 |
| 11 | A Hold „kemikália- és sugárzásmentes” környezet. | A Holdon erős a kozmikus és a napsugárzás, mert nincs légkör és mágneses tér. A sugárvédelem fontos tervezési szempont. | 02, 6. fejezet |
| 12 | A forgó mágneses tér „vonzza” a fém űrszemetet. | Az alumíniumot (a műholdak fő anyagát) a mágnes nem vonzza. A forgó tér örvényáramokat kelt, amelyek fékezik a forgást. Ez éppen a pörgő roncsok megnyugtatására jó. | 03, 3.1 |
| 13 | 70–90%-os újrahasznosítási arány érhető el. | Mérés nélkül nem állítható. A javított változat ezt nyitott kérdésként kezeli. | 02, 7. fejezet |

## Amit szándékosan nem vettünk át

Az időszak más, az űrszeméthez kapcsolódó ötletvázlatai — például **annihilációs hajtómű**, **nukleáris hulladékból készülő termonukleáris akkumulátor**, illetve a kozmikus sugárzás „hasznosítása” élelmiszer-előállításra — a jelenlegi fizikai ismeretek alapján nem kidolgozható mérnöki koncepciók. Ezeket nem publikáljuk.

Az eredeti szövegek politikai jellegű állításait (például a nyersanyagok gazdasági kisajátításának megakadályozásáról) szintén kihagytuk, mert egy műszaki koncepció bemutatásához nem szükségesek.

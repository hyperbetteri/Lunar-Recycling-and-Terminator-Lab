# Korábbi ötletek: űrszemét-begyűjtés érintésmentes erőterekkel

**Ötletvázlat (2024. november) — javított, műszakilag átnézett változat**

Szerző: Almási Andor · Eredeti vázlat: 2024. november · Javított változat: 2026. október

> Ez a dokumentum a holdi labor előzményét mutatja be: 2024 végén az ötlet a Föld körüli űrszemét érintésmentes befogásával indult. Az eredeti, AI-motorok segítségével megfogalmazott szövegben a fizikai magyarázat egy ponton hibás volt; ezt itt javítottuk.

## 1. A probléma

A Föld körül több tízezer nyomon követett, ennél sokkal több apró darab űrszemét kering. Ezek veszélyeztetik a működő műholdakat, és ütközéskor újabb törmeléket hoznak létre. A begyűjtés egyik nehézsége, hogy a régi műholdak és rakétafokozatok gyakran **pörögnek, bukdácsolnak**, ezért nehéz őket megfogni.

## 2. Az eredeti ötlet

Két érintésmentes erőtér együttes használata, napenergiával működtetve:

1. **Forgó mágneses tér** a fémes darabokhoz.
2. **Elektrosztatikus tér** a nem mágneses darabokhoz (műanyag, kompozit).

## 3. Mi a helyes fizikai magyarázat?

### 3.1. Forgó mágneses tér: nem vonz, hanem lassít

Az eredeti szöveg azt írta, hogy a forgó mágneses tér „vonzza” a fémeket. Ez az űrszemét nagy részére **nem igaz**: az alumínium, amelyből a legtöbb műholdszerkezet készül, nem ferromágneses, a mágnes nem húzza.

A valódi hatás más, és éppen ezért hasznos: a változó mágneses tér a fémben **örvényáramokat** kelt, és ezek a Lenz-törvény szerint **fékezik a tárgy mozgását a térhez képest**. Ez alkalmas arra, hogy egy pörgő, bukdácsoló műholdroncs forgását érintés nélkül lelassítsuk. Ezt a szakirodalom **örvényáramos forgáscsillapításnak** (eddy-current detumbling) nevezi, és valóban kutatott technológia. A megnyugtatott roncsot utána már biztonságosan meg lehet fogni.

### 3.2. Elektrosztatikus tér: érintésmentes vontatás

A feltöltött begyűjtő egység és a szintén feltöltött tárgy közötti elektrosztatikus erő **gyenge, de folyamatos** húzóerőt ad. Ez néhány tíz méteres távolságból képes lassan elmozdítani nagy tömegű tárgyakat is, például geostacionárius pályáról temetőpályára. A szakirodalomban ez az **elektrosztatikus vontatás** (electrostatic tractor) koncepciója.

### 3.3. Napenergia

A napelemek valóban alkalmasak a rendszer táplálására. Az erős mágneses terekhez azonban nagy áram és hűtés kell, ezért a teljesítményigényt minden esetben számítással kell igazolni.

## 4. A javított koncepció

| Lépés | Eszköz | Cél |
|---|---|---|
| 1. Megközelítés | Begyűjtő egység napelemes táplálással | A roncs közelébe jutni |
| 2. Megnyugtatás | Forgó mágneses tér (örvényáramos fékezés) | A pörgés lelassítása érintés nélkül |
| 3. Elmozdítás | Elektrosztatikus vontatás, illetve megfogás karral vagy hálóval | A roncs pályájának megváltoztatása |
| 4. Végcél | Légkörbe vezetés kontrollált visszatéréssel, temetőpálya, vagy feldolgozás | A veszély megszüntetése |

## 5. Miért vezetett ez a holdi laborhoz?

Az ötlet továbbgondolása során felmerült, hogy a begyűjtött anyagot ne elégessük a légkörben, hanem **hasznosítsuk**. Ez vezetett a [terminátorkövető holdi labor](01_Terminatorkoveto_holdi_labor.md) koncepciójához. A számítások szerint azonban a Föld körüli szemét Holdra szállítása nagyon energiaigényes, ezért a holdi feldolgozás elsősorban a holdbázison keletkező hulladékra épül (lásd: [02 – LunaRecycle koncepció](02_LunaRecycle_hulladekfeldolgozasi_koncepcio.md)).

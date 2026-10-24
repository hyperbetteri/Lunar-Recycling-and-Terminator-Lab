**Language / Nyelv:** [English](02_LunaRecycle_hulladekfeldolgozasi_koncepcio.en.md) · [Magyar](02_LunaRecycle_hulladekfeldolgozasi_koncepcio.md)

# Lunar Waste Processing Concept for the NASA LunaRecycle Challenge

**Concept study — corrected, technically reviewed version**

Author: Almási Andor · Original materials: February–March 2025 · Corrected version: October 2026

> **Background.** The NASA LunaRecycle Challenge (part of the Centennial Challenges program) seeks solutions that convert solid waste generated at a lunar base into useful materials or products. This document is a corrected version of materials prepared during a Hungarian team's preparation for the 2025 challenge. The materials were prepared at the request of **Dr. Jenő Páli**, who organised and registered the Lunar Team Hungary team and represented it as team leader, worked through the challenge announcement and selected the three waste items to be processed. The original texts, drafted with the help of AI engines, contained several technical errors; these are listed in the [04 – Correction log](04_Javitasi_naplo.en.md).

## The team and the application

Source: Dr. Jenő Páli's emails of February–March 2025.

- **Team:** Lunar Team Hungary. Dr. Jenő Páli registered the team on the NASA Centennial Challenges website (registration number: #670) and represented it as Team Leader.
- **Hungarian participation:** no Hungarian team had yet entered any of the 23 NASA Centennial Challenges held up to that point (according to Dr. Jenő Páli).
- **Administrator:** the challenge was administered by The University of Alabama. To participate, the team had to sign a 16-page participation agreement (Phase 1 Team Agreement) with the university.
- **Official site:** [lunarecyclechallenge.ua.edu](https://lunarecyclechallenge.ua.edu/#project) · news article in Hungarian: [origo.hu](https://www.origo.hu/tudomany/2024/10/nasa-verseny-hold)
- **Deadline (Phase 1):** 31 March 2025 — submission of the application and the proposed solution.
- **Prizes:** only US citizens and companies are eligible for prize money; non-US teams may also compete, but they can receive recognition.
- **Eligibility requirements:** every team member had to register individually, verifying their identity and citizenship, and the team had to provide evidence of insurance or financial coverage of USD 5,000 (Proof of Insurance / Proof of Funds).
- **Working through the announcement:** Dr. Jenő Páli read the 44-page challenge announcement (Phase 1 Rules) in full, highlighted the relevant parts, and contacted the organisers about the participation requirements that were still unclear.

## 1. Challenge framework (based on the public announcement)

**Reference mission:** a crew of 8, a 1-year stay on the Moon. The announcement lists 6 waste categories and 17 waste items, with exact material compositions.

**Two environments:**

| | Pressurised habitat module (interior) | Lunar surface (exterior) |
|---|---|---|
| Gravity | 1.625 m/s² | 1.625 m/s² |
| Pressure | 57.2 kPa | 0.3 nPa (practically a vacuum) |
| Temperature | 18–27 °C | 50–250 K (approx. −223 °C to −23 °C) |
| Atmosphere composition | ~34% O₂, ~66% N₂ | — |
| Size limit | 4 EXPRESS rack double lockers (the standard experiment locker of the International Space Station, each approx. 48 × 42 × 24 cm) | none |

The external temperature range in the rules (50–250 K) does not include the equatorial daytime peak (about +120 °C, see [document 01](01_Terminatorkoveto_holdi_labor.en.md)); it matches polar conditions.

**Key rules:**

- the waste **must not be incinerated**;
- toxic emissions, **PFAS compounds** (per- and polyfluoroalkyl substances) and **microplastics** must be avoided; if they are nonetheless generated, this must be declared;
- lunar **regolith** (the loose rock dust and debris covering the lunar surface) may be used freely, in any quantity (specification: [LHS-1](https://sciences.ucf.edu/class/wp-content/uploads/sites/23/2019/02/Spec_LHS-1.pdf));
- in the first phase, lunar dust does not need to be addressed separately, but a proposal must be made for **protection against lunar dust**;
- the design submitted in the first phase is not a prerequisite for the second phase (building a prototype): teams may enter that phase with a different idea, process and waste type.

**Expected products (examples from the announcement):** kitchen utensils, towels, wipes, nitrile gloves, containers for food, water, chemicals and gases, utility and assembly tools (cable ties, straps, harnesses, wrenches, screws), as well as everyday items that would otherwise not be sent to space for cost reasons.

## 2. The three selected waste items

Dr. Jenő Páli selected three of the 17 items in the 6 waste categories, one from each of the three difficulty levels:

| Item | Quantity (1 year, 8 crew) | Difficulty | Material |
|---|---|---|---|
| **Zotek F30 foam packaging** | ~10 m³ / ~1000 kg | 3 (hardest) | PVDF foam (fluoropolymer); according to the manufacturer it is cross-linked, i.e. its molecular chains are joined together by crosslinks |
| **Aluminium structural elements** | ~9 m³ / ~900 kg | 2 (medium) | >90% aluminium |
| **Nitrile gloves** | ~0.22 m³ / ~41 kg | 1 (easiest) | nitrile rubber |

Material properties referenced by the announcement: [Zotek F (manufacturer's page)](https://www.zotefoams.com/product/zotek/zotek-f-lightweight-pvdf-foam/) · [nitrile glove safety data sheet](https://www.medpride.com/media/MSDS-NITRILE-PF-EXAM-GLOVE-5050X.pdf)

## 3. The basic principle: cold preparation, solar heat

The Moon offers two "free" resources that are expensive to produce on Earth:

- **Cold:** on the shaded side and at night the temperature can drop below 100 K (−173 °C). At this temperature most plastics and rubbers become **glass-like and brittle**, and can easily be ground mechanically into powder. This is called cryogenic grinding; on Earth it requires liquid nitrogen, whereas on the Moon the natural cold is sufficient.
- **Concentrated sunlight:** without an atmosphere, sunlight collected with mirrors or Fresnel lenses can raise temperatures **above a thousand degrees**. This is sufficient both for melting metal and for sintering regolith.

The [terminator-following lab](01_Terminatorkoveto_holdi_labor.en.md) provides continuous access to both: sunlight on one side, shade on the other.

## 4. Processing routes

### 4.1. Zotek F30 (PVDF foam) — mechanical route, without thermal decomposition

PVDF is a fluoropolymer. **When heated (above about 350 °C) it releases hydrogen fluoride (HF)**, which is highly toxic and corrosive. Under some international definitions, PVDF itself qualifies as a PFAS. The proposed route therefore **does not break the material down chemically**, but transforms it mechanically:

1. **Cryogenic grinding** in a closed mill: the foam, made brittle by the cold, is ground into fine particles.
2. **Composite production:** the PVDF regrind is mixed with lunar regolith and, as a binder, polyethylene recovered from the waste (the announcement lists several pure polyethylene waste items, e.g. bubble wrap and air pillows).
3. **Hot pressing** at a moderate temperature (150–200 °C), well below the decomposition temperature of PVDF.
4. **Products:** thermal insulation panels, cladding tiles, pipe supports, trays, spacers.

**Risks to be declared:** grinding produces microplastic dust, so the process runs in a closed system with dust extraction, and all of the dust is incorporated into the composite. Since the feedstock is a fluoropolymer, the PFAS content must be declared in the submission.

### 4.2. Aluminium — melting in a solar furnace

1. Cutting and cleaning.
2. **Melting** (660 °C) in a furnace powered by concentrated sunlight, or in an induction furnace, under shielding gas or in a vacuum.
3. **Products:** cast parts (wrench, bracket, support) or wire. From the wire, a metal 3D printer (wire arc additive manufacturing) can produce any part: it melts the wire with an electric arc and builds up the object layer by layer. The arc process needs a shielding gas; in vacuum, electron-beam wire additive manufacturing (EBAM) is the more natural choice.

The external vacuum is an advantage: the melt does not oxidise.

### 4.3. Nitrile gloves — rubber crumb

1. Disinfection and cryogenic grinding into rubber crumb.
2. Mixing with a binder, then pressing.
3. **Products:** anti-slip mats, vibration-damping inserts, sealing rings.

## 5. Power and heat — corrected solution

| Task | Temperature | Proposed source |
|---|---|---|
| Cryogenic grinding | below 150 K (−123 °C) | Shaded-side radiative cooling |
| Polymer hot pressing | 150–200 °C | Electric heating from solar panels, or a low-concentration solar collector |
| Aluminium melting | ~700 °C | Concentrated sunlight (solar furnace) |
| Regolith sintering | ~1100 °C | Concentrated sunlight |

## 6. Protection against lunar dust

Lunar dust has sharp-edged grains, becomes electrostatically charged and gets into every gap. Proposed protection:

- **Electrodynamic dust shield:** electrodes embedded in the surface sweep the dust away using alternating voltage. NASA has already tested this technology.
- Sealed bearings and moving parts with labyrinth seals.
- An airlock for feeding in the waste, with dust separation.
- Interior processing runs in the pressurised module; only the solar furnace and the radiator surfaces are outside.

## 7. What we do not claim

- We do not claim an exact recycling rate. The 70–90% values in the original texts were estimates, without measurement.
- The processing routes have not yet been verified by laboratory experiment. The next step would be a ground-based experiment: cryogenic grinding of PVDF foam, followed by pressing a composite mixed with regolith simulant and testing its strength.

## 8. Summary

The corrected concept builds on two natural advantages of the Moon: **cold**, which makes grinding simple, and **concentrated sunlight**, which enables high-temperature processing. For the hardest item, PVDF foam, it deliberately **avoids thermal decomposition**, thereby preventing the formation of toxic hydrogen fluoride, and handles PFAS content and microplastic dust in line with the challenge's declaration rule.

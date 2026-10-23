**Language / Nyelv:** [English](01_Terminatorkoveto_holdi_labor.en.md) · [Magyar](01_Terminatorkoveto_holdi_labor.md)

# Terminator-Following Lunar Research and Recycling Lab

**Concept study — corrected, technically reviewed version**

Author: Almási Andor · Original concept: February 2025 · Corrected version: October 2026

> **Note.** The original materials were prepared in early 2025 with the help of AI engines. This version keeps the core idea but corrects the physical and engineering claims using verified calculations. The list of corrections made: [04 – Correction log](04_Javitasi_naplo.en.md).

## 1. The core idea

On the Moon, one day (from sunrise to sunrise) lasts about **29.5 Earth days**. A base at a fixed location is therefore in sunlight for roughly two weeks and then in darkness for two weeks: during the day the surface heats up to around +120 °C, and at night it cools below −170 °C.

The **terminator line** is the boundary between the day side and the night side. If a mobile lab follows this line, it **never enters the two-week lunar night**, and it does not have to endure the daytime temperature peak either. It receives continuous sunlight for power, while there is always shade and cold in its immediate vicinity, which is useful for heat rejection and for cold-based technologies.

**So the essence of the idea is:** instead of trying to survive the lunar night with huge batteries, avoid it — travel along the boundary between day and night.

## 2. Why near the poles? — the key calculation

The closer we are to a pole, the more slowly the terminator line moves across the lunar surface. Its speed is:

```
v(φ) = 2π · R_Moon · cos(φ) / T_synodic
R_Moon ≈ 1737 km  (radius of the Moon)
T_synodic ≈ 29.53 days ≈ 708.7 hours  (length of one lunar day, from sunrise to sunrise)
φ = latitude on the Moon
```

| Latitude (φ) | Speed of the terminator | Length of one full loop |
|---|---|---|
| 0° (equator) | ≈ 15.4 km/h | ≈ 10,900 km |
| 80° | ≈ 2.7 km/h | ≈ 1,900 km |
| 85° | ≈ 1.3 km/h | ≈ 950 km |
| 88° | ≈ 0.5 km/h | ≈ 380 km |
| 89° | ≈ 0.27 km/h | ≈ 190 km |

**This is the strongest argument for the concept.** At the equator a lab would have to travel continuously at ~15 km/h, which is unrealistic for a heavy industrial facility. Near the pole, however — for example at the 88th–89th parallel — movement **slower than walking pace** is sufficient, and the full loop is only a few hundred kilometres. This can be followed even by a heavy, slow-moving platform.

Moreover, the Moon's axial tilt is only about 1.5°, so near the poles the Sun always stays close to the horizon. Some elevated sites receive almost continuous illumination — the literature calls these *peaks of eternal light*, which simply means that there the Sun does not set below the horizon for most of the year. Meanwhile, deep inside nearby craters there are permanently shadowed, extremely cold areas (about 25–40 K, i.e. around −250 °C) that may contain water ice. The polar region thus provides **energy, cold and water** at the same time.

## 3. Locomotion: levitated track or wheeled platform?

The original plan proposed a superconducting magnetic levitation (maglev) track. This is interesting as a long-term vision, but it has two limitations:

1. **Superconductor temperature.** The high-temperature superconductors used in practice (e.g. the ceramic known as YBCO) have a critical temperature of about 92 K (−181 °C) and a typical operating temperature of 65–77 K. −150 °C (123 K) is **not cold enough** for this. Such temperatures can be reached with radiative cooling surfaces and refrigerators specifically designed for very low temperatures (cryocoolers), but they do not come about "on their own".
2. **Size of the track.** Even a 190 km loop requires an enormous amount of track material, which would have to be launched from Earth or manufactured on site.

**Proposed staged solution:**

| Phase | Locomotion | Rationale |
|---|---|---|
| 1. | Slow wheeled or tracked platform | The required speed of 0.3–1.3 km/h is easily achieved with wheels, without a track. |
| 2. | Chain of modular units | Several smaller modules travel together; a single failed unit does not stop the whole system. |
| 3. | Locally manufactured track, later levitation | Once building elements can be produced from regolith (the loose rock dust and debris covering the lunar surface), the track can be built out gradually. |

## 4. Power and heat

- **Solar panels:** near the pole the Sun is low in the sky, so **vertical, rotatable solar panels** are needed that track the Sun's direction. Because the lab follows the terminator, they generate power practically continuously.
- **Energy storage:** since the lab avoids the two-week night, storage is needed only for short outages (terrain shadowing, maintenance). Batteries are sufficient for this. Supercapacitors are suitable only for short peak loads; their energy density is too low for longer-term storage.
- **Heat rejection:** radiator surfaces facing the shaded side reject heat to the cold sky. This is a natural advantage of the site.
- **High temperature:** in the absence of an atmosphere, **concentrated sunlight** (mirrors or flat collecting lenses, so-called Fresnel lenses) readily produces temperatures above a thousand degrees. This is suitable for melting aluminium (660 °C) and for sintering regolith, i.e. baking the dust into a solid block by heating it below its melting point. This solution is far more efficient than heat pumps (see the correction log).

## 5. What would the lab process?

The original concept also raised the idea of transporting space debris from Earth orbit to the Moon. An honest engineering assessment shows that this is **energetically very expensive**: delivering an object from low Earth orbit to the lunar surface requires a velocity change (delta-v) of roughly 5.5–6 km/s, which is nearly as much as a complete lunar mission.

The realistic order of priorities is therefore:

1. **Waste generated at the lunar base** — packaging materials, textiles, structural elements. This is exactly what the NASA LunaRecycle Challenge targets (see the [02 – LunaRecycle concept](02_LunaRecycle_hulladekfeldolgozasi_koncepcio.en.md) document).
2. **Human-made hardware already on the Moon** — old landers, impacted rocket stages. Estimates put their total mass at more than 180 tonnes.
3. **In the long term**, hardware in lunar orbit, and only in the very long term, space debris in Earth orbit.

## 6. Artificial intelligence in the system

One of the lab's goals is to be largely autonomous. The roles of AI:

- **Navigation:** predicting the terminator and terrain shadows, route planning.
- **Material identification:** sorting incoming waste (spectral and optical sensing).
- **Process control:** controlling grinding, melting and forming.
- **Resource management:** allocating power, heat and supplies.

Human oversight is retained at every decision point. The author's validation work with multiple AI engines shows precisely that AI outputs must be verified, not executed blindly.

## 7. Open questions

- An accurate shadow map of the polar terrain along the chosen route.
- Protection of moving parts against lunar dust (see 02, Section 6).
- The mass of the platform and the minimum initial equipment to be delivered from Earth.
- Ensuring communication with Earth near the pole (a relay satellite may be required).

## 8. Summary

The core idea of the terminator-following lab is **physically sound**, and near the poles it is **realistic from an engineering standpoint as well**: there the required speed is below walking pace, the full route is a few hundred kilometres, and the environment provides sunlight, cold and water ice at the same time. The corrected concept starts with a wheeled, modular platform, uses concentrated sunlight for high-temperature processing, and primarily processes waste generated at the lunar base.

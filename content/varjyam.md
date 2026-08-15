---
id: panchang.varjyam
canonical_term: Varjyam
title: Varjyam (वर्ज्यम्) — Meaning, Calculation and Traditional Use
slug: varjyam
category: muhurta
aliases:
  - Varjyam
  - Visha Ghati
  - Tyajyam
  - Tyajyakala
  - Nakshatra Tyajya
  - वर्ज्यम्
  - विष घटि
languages: [hi, en]
status: reviewed
last_reviewed: 2026-08-15
calculation:
  engine_key: varjyam
  dynamic: true
  location_sensitive: true
related_concepts:
  - Nakshatra
  - Amrit Kaal
  - Rahu Kaal
  - Tarabala
  - Lagna Tyajya
  - Panchanga Shuddhi
sources:
  - name: Supplied research material
    type: supplied-source
    note: Detailed Varjyam definition, 27-Nakshatra ghati-start table, calculation, practical use and related concepts.
  - name: B. V. Raman — Muhurtha (Electional Astrology)
    type: supplied-source
    note: Referenced for Tyajyakala/Tarabala-related context in the supplied material.
---

# Varjyam (वर्ज्यम्)

## 1. What Is It?

**Varjyam**, also called **Visha Ghati**, **Tyajyam**, **Tyajyakala** or **Nakshatra Tyajya**, is a traditional Nakshatra-related interval treated as unsuitable for selected auspicious beginnings.

The supplied material describes Varjyam as a specific interval occurring during each Nakshatra transit. It is calculated using a traditional 60-ghati framework, with a Nakshatra-specific starting ghati and a duration of 4 ghatis.

Varjyam is therefore a **Nakshatra-based intraday timing rule**, distinct from daily periods such as Rahu Kaal, Yamaganda and Gulika Kaal.

## 2. Why Does It Exist?

Traditional Muhurtha practice treats different portions of Nakshatra transit as having different qualities. Varjyam identifies the portion traditionally regarded as unsuitable for selected important or auspicious undertakings.

The supplied research explains this through a traditional model involving lunar consciousness, Nakshatra boundaries and subtle or electromagnetic influences. Those explanations should be presented as **traditional interpretation**, not as established physical science.

The practical purpose is to avoid deliberately initiating selected important activities during the applicable Varjyam interval when another suitable time is available.

## 3. How Is It Calculated?

The calculation requires the actual local start and end times of the current Nakshatra and the traditional Varjyam starting-ghati value assigned to that Nakshatra.

Let:

- `T_total` = total duration of the Nakshatra transit in minutes.
- `G_start` = Nakshatra-specific starting ghati.

Then:

`one_ghati = T_total / 60`

`Varjyam start = Nakshatra start + (G_start / 60) × T_total`

`Varjyam duration = (4 / 60) × T_total`

`Varjyam end = Varjyam start + Varjyam duration`

The 4-ghati duration is therefore **not a fixed 96 minutes** unless the full Nakshatra transit itself lasts exactly 24 hours. Because the Moon's angular speed varies, Nakshatra transit durations vary, and so does the civil-clock duration of the 4-ghati interval.

### Traditional starting-ghati table

| Nakshatra | Starting ghati |
|---|---:|
| Ashwini | 50 |
| Bharani | 24 |
| Krittika | 30 |
| Rohini | 40 |
| Mrigashira | 14 |
| Ardra | 21 |
| Punarvasu | 30 |
| Pushya | 20 |
| Ashlesha | 32 |
| Magha | 30 |
| Purva Phalguni | 20 |
| Uttara Phalguni | 18 |
| Hasta | 22 |
| Chitra | 20 |
| Swati | 14 |
| Vishakha | 14 |
| Anuradha | 10 |
| Jyeshtha | 14 |
| Mula | 20 |
| Purva Ashadha | 24 |
| Uttara Ashadha | 20 |
| Shravana | 10 |
| Dhanishtha | 10 |
| Shatabhisha | 18 |
| Purva Bhadrapada | 16 |
| Uttara Bhadrapada | 24 |
| Revati | 30 |

### Worked example from supplied material

Suppose Rohini begins at 06:00 and ends at 08:00 the following day.

- `T_total = 26 hours = 1560 minutes`
- Rohini `G_start = 40`
- Varjyam start = `06:00 + (40/60 × 1560)` = **23:20**
- Varjyam duration = `(4/60 × 1560)` = **104 minutes**
- Varjyam end = **01:04** the following day

Therefore, under the supplied example, Rohini Varjyam is **23:20–01:04**.

The production engine should use actual Nakshatra boundary instants from the astronomical engine rather than rounded examples.

## 4. How Can a Normal Person Use It?

For a normal user, the practical rule is simple:

**When planning a major auspicious beginning, avoid the local Varjyam interval shown by the Panchang when a reasonable alternative exists.**

The supplied material lists the following as activities traditionally avoided during Varjyam:

- starting a new business or major undertaking;
- marriage and other major auspicious ceremonies;
- house construction or Griha Pravesh;
- Mundan and Upanayana;
- beginning a major financial agreement or investment;
- starting an important journey.

It also states that Varjyam is not a blanket prohibition on all activity.

### Activities that may continue

The supplied material allows for:

- ongoing work;
- routine daily activity;
- review and correction of previously completed work;
- background preparation.

It also cites an emergency rule attributed to the Raman tradition: where a highly important task is otherwise strongly supported by Tara Bala and Chandra Bala, the specific Varjyam interval can be avoided and the remaining part of the Nakshatra may be used.

## 5. Common Misconceptions

### Varjyam is a fixed 96-minute clock period

No. The supplied material expresses it as 4 ghatis of the Nakshatra transit. The actual civil-clock duration depends on the total Nakshatra transit duration.

### The entire Nakshatra becomes unusable when Varjyam occurs

No. The supplied rule targets the specific Varjyam interval, not the entire Nakshatra transit.

### Varjyam is calculated only for inauspicious Nakshatras

No. The supplied table assigns a Varjyam starting point to all 27 routinely used Nakshatras, including traditionally auspicious Nakshatras such as Rohini, Pushya and Hasta.

### Varjyam and Tarabala's temporary restrictions are the same rule

No. The supplied research explicitly distinguishes the normal Nakshatra Varjyam interval from special Tarabala-related restrictions in which only specified ghatis may be treated as unfavourable.

## 6. Important Distinctions

### Varjyam vs Amrit Kaal

The supplied material presents Varjyam and Amrit Kaal as separate Nakshatra-related periods. It describes Amrit Kaal as another specific interval associated with the Nakshatra rather than simply calling the entire remaining Nakshatra universally auspicious.

The exact relationship between the two should be exposed according to the adopted traditional rule set rather than inferred from the names alone.

### Varjyam vs Rahu Kaal

- **Varjyam:** based on the Moon's current Nakshatra transit and a Nakshatra-specific ghati rule.
- **Rahu Kaal:** based on local sunrise/sunset, weekday and an eight-part daylight division.

### Varjyam vs Lagna Tyajya

- **Nakshatra Tyajya / Varjyam:** a Moon-Nakshatra-based interval.
- **Lagna Tyajya:** specified degrees/segments of the rising sign in electional astrology.

### Varjyam vs Tarabala

Tarabala compares the day's Nakshatra with a person's Janma Nakshatra and can introduce separate restrictions or suitability classifications. Varjyam is the specific Nakshatra-transit interval described in this page.

## 7. Traditional Interpretation

Traditional Muhurtha practice treats Varjyam as a time to avoid for selected auspicious beginnings.

The supplied research also uses language about subtle lunar effects, electromagnetic influences and negative energy. Those statements should be presented as **traditional explanatory models**, not established scientific mechanisms.

The calculational fact is simpler: Varjyam is a dynamically computed time interval derived from the current Nakshatra's transit duration and its traditional starting-ghati value.

## 8. Variations and Disagreements

The supplied material primarily documents one traditional starting-ghati table for the 27 Nakshatras.

It also distinguishes Varjyam from separate Tarabala restrictions and records a Raman-related emergency rule in which the specific Tyajyakala can be skipped while the remainder of an otherwise favourable Nakshatra remains usable.

For Panchang.cloud, the calculation rule and the interpretive/exception layer should be kept separate so that different traditions can be supported without changing the astronomical timing calculation.

## 9. Today's Calculation

`Dynamic Panchang calculation required.`

The engine should:

1. Determine the current Nakshatra and its exact start/end instants.
2. Identify the Nakshatra's starting-ghati value from the canonical table.
3. Calculate the 4-ghati Varjyam interval.
4. Convert the result into the user's local civil time.

Recommended engine contract:

`varjyam(date, latitude, longitude, timezone, tradition="default")`

## 10. Related Concepts

- Nakshatra (नक्षत्र)
- Visha Ghati (विष घटि)
- Amrit Kaal (अमृत काल)
- Rahu Kaal (राहु काल)
- Tarabala (ताराबल)
- Lagna Tyajya (लग्न त्याज्य)
- Panchanga Shuddhi (पञ्चाङ्ग शुद्धि)

## 11. Knowledge-Base Summary

- **Canonical Name:** Varjyam (वर्ज्यम्)
- **Aliases:** Visha Ghati, Tyajyam, Tyajyakala, Nakshatra Tyajya
- **Category:** Nakshatra-based Inauspicious Period
- **What it is:** A traditional interval occurring during each Nakshatra transit and treated as unsuitable for selected auspicious beginnings.
- **Why it exists:** It is used as a Nakshatra-based time filter in traditional Muhurtha.
- **How it is determined:** Use the current Nakshatra's actual transit duration, apply its traditional starting-ghati value, and calculate a 4-ghati interval.
- **Primary traditional purpose:** Avoid selected important or auspicious commencements during the Varjyam interval.
- **Practical use:** Schedule major beginnings outside the local Varjyam period where practical.
- **Important exceptions:** Ongoing work is not automatically prohibited; the supplied Raman-related emergency rule permits use of the rest of a favourable Nakshatra after the specific Tyajyakala has passed.
- **Common misconceptions:** It is not a fixed 96-minute clock period and does not make the entire Nakshatra unusable.
- **Related concepts:** Nakshatra, Visha Ghati, Amrit Kaal, Rahu Kaal, Tarabala, Lagna Tyajya.
- **Calculation-dependent:** Yes
- **Location-dependent:** Yes

## Provenance Note

This entry incorporates the supplied Varjyam research material, including the 27-Nakshatra starting-ghati table and worked example. Traditional explanatory claims are retained as traditional interpretation rather than scientific fact. The calculation layer is separated from the interpretive layer so the knowledge engine can render the timing independently of tradition-specific advice.

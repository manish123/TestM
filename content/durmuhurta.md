---
id: panchang.durmuhurta
canonical_term: Durmuhurta
title: Durmuhurta (दुर्मुहूर्त) — Meaning, Calculation and Traditional Use
slug: durmuhurta
category: muhurta
aliases:
  - Durmuhurta
  - Durmuhurtham
  - दुर्मुहूर्त
languages: [hi, en]
status: established
last_reviewed: 2026-08-15
calculation:
  engine_key: durmuhurta
  dynamic: true
  location_sensitive: true
related_concepts:
  - Muhurta
  - Abhijit Muhurta
  - Rahu Kaal
  - Yamaganda
  - Gulika Kaal
  - Varjyam
  - Panchanga Shuddhi
sources:
  - name: B. V. Raman — Muhurtha (Electional Astrology)
    type: supplied-source
    note: Provides a classical Durmuhurta framework and weekday-specific allocations.
  - name: Established Panchanga practice / Drik Panchanga convention
    type: panchanga-reference
    note: Provides the alternate commonly used daytime 15-part allocation documented separately below.

# Durmuhurta (दुर्मुहूर्त)

## 1. What Is It?

**Durmuhurta** is a traditionally inauspicious time interval used in Hindu Muhurtha practice. The term combines *dur* (bad, difficult or unfavourable) with *muhurta* (a traditional time unit).

A full ahoratra is traditionally divided into 30 Muhurtas: 15 daytime Muhurtas and 15 nighttime Muhurtas. A Muhurta is therefore 1/30 of an ahoratra; in the conventional 24-hour model this is 48 minutes. When daytime Muhurtas are calculated dynamically, their actual duration is the local daylight duration divided by 15.

Durmuhurta is an additional Muhurtha consideration and should not be confused with one of the five Panchanga limbs (Tithi, Vara, Nakshatra, Yoga and Karana).

## 2. Why Does It Exist?

Traditional Muhurtha practice classifies portions of the day according to their suitability for particular activities. Durmuhurta identifies intervals traditionally avoided for commencing important or auspicious undertakings.

The traditional material associates the period with unfavourable or conflicting qualities. Such explanations belong to the traditional interpretive framework. Claims about electromagnetic, biological or physical mechanisms should not be presented as established scientific facts.

The practical purpose is narrower: when a major commencement is being deliberately timed, choose a suitable alternative period rather than a Durmuhurta interval where the applicable tradition requires avoidance.

## 3. How Is It Calculated?

The daytime calculation requires:

1. Local sunrise `S`.
2. Local sunset `T`.
3. The local weekday.
4. The selected Durmuhurta convention.

Daylight duration:

`D = T - S`

One daytime Muhurta:

`M = D / 15`

For a specified daytime Muhurta number `N`:

`start = S + (N - 1) × M`

`end = S + N × M`

Thus, a 48-minute duration occurs only when daylight is exactly 12 hours. Actual clock intervals vary with date and location.

### Method A — Common Drik Panchanga-style daytime allocation

| Weekday | Durmuhurta daytime segment(s) |
|---|---:|
| Sunday | 14th |
| Monday | 9th, 12th |
| Tuesday | 2nd, 5th |
| Wednesday | 12th |
| Thursday | 6th |
| Friday | 4th, 9th |
| Saturday | 1st |

The supplied source identifies these segments with the corresponding named daytime Muhurtas.

### Method B — B. V. Raman / supplied Muhurtha allocation

The supplied Raman-based material gives a different weekday allocation:

| Weekday | Durmuhurta daytime segment(s) |
|---|---:|
| Sunday | 14th |
| Monday | 8th, 12th |
| Tuesday | 4th, 11th |
| Wednesday | 8th |
| Thursday | 12th, 13th |
| Friday | 4th, 8th |
| Saturday | 1st, 2nd |

Because the two supplied traditions produce different segment assignments, a production Panchang engine should **not silently merge them**. The calculation engine should expose the convention explicitly, for example `drik` and `raman`, and the UI should identify which method produced the displayed interval.

### Worked example — 12-hour Sunday

For sunrise at 06:00 and sunset at 18:00:

- `D = 12 hours = 720 minutes`
- `M = 720 / 15 = 48 minutes`
- Sunday uses the 14th segment in both documented methods.
- Start = `06:00 + 13 × 48 min = 16:24`
- End = `16:24 + 48 min = 17:12`

Therefore the Sunday Durmuhurta interval in this simplified example is **16:24–17:12**.

## 4. How Can a Normal Person Use It?

If following a tradition that observes Durmuhurta, the practical rule is to avoid deliberately commencing major or auspicious activities during the applicable interval when a reasonable alternative exists.

Traditional avoidance may include:

- starting a new business, office or major project;
- commencing an important journey;
- signing an important agreement;
- beginning major ceremonies such as marriage, Griha Pravesh, Upanayana or Mundan;
- scheduling a major commencement where the Muhurtha is being intentionally selected.

Durmuhurta does **not** imply that ordinary life must stop. Ongoing work, routine activity, review, correction and unavoidable actions are not equivalent to deliberately selecting Durmuhurta for a major commencement.

For a full Muhurtha, Durmuhurta should be considered together with the other applicable Panchanga and Muhurtha rules rather than used as the sole criterion.

## 5. Common Misconceptions

### Durmuhurta occurs at a fixed clock time every day

No. When calculated from local sunrise and sunset, the actual clock interval changes with date and location.

### Durmuhurta means all activity must stop

No. The principal practical concern is commencement of selected important or auspicious activities. Routine and already-running work are not automatically prohibited.

### Durmuhurta is one of the five Panchanga limbs

No. It is a Muhurtha/timing consideration. The five Panchanga limbs are Tithi, Vara, Nakshatra, Yoga and Karana.

### There is only one universally identical Durmuhurta table

The supplied material documents two different allocations: a Drik Panchanga-style convention and a B. V. Raman/supplied Muhurtha convention. They should be preserved as distinct methods.

### Wednesday's Abhijit interval is universally Durmuhurta

This is **method-dependent in the supplied material**. The Raman-based table identifies the 8th daytime Muhurta as Durmuhurta on Wednesday, while the alternative table assigns Wednesday the 12th segment. Therefore the knowledge base must not state this as an unqualified universal rule.

## 6. Important Distinctions

### Durmuhurta vs Rahu Kaal

Durmuhurta is based on the traditional daytime Muhurta framework, normally using a 15-fold division of daylight. Rahu Kaal uses an eight-part division of daylight and has a different weekday allocation.

### Durmuhurta vs Yamaganda

Yamaganda uses an eight-part division of daylight and a different weekday allocation. It is not the same calculation as Durmuhurta.

### Durmuhurta vs Muhurta

*Muhurta* is the traditional unit of time. *Durmuhurta* identifies intervals traditionally regarded as unfavourable within the Muhurtha framework.

### Durmuhurta vs Abhijit Muhurta

Abhijit Muhurta is a separate traditionally favourable midday interval. A method that assigns a particular Muhurta number as Durmuhurta must be kept distinct from generic statements about Abhijit being favourable.

## 7. Traditional Interpretation

Traditional Muhurtha texts treat Durmuhurta as a period to be avoided for specified auspicious beginnings.

The supplied material also contains explanations involving planetary conflict, electromagnetic balance and biological effects. These should be labelled as traditional interpretation rather than astronomical or scientifically established mechanisms.

The calculational fact is simpler: the interval is produced by applying a specified weekday allocation to the local daytime Muhurta divisions.

## 8. Variations and Disagreements

The principal documented variation for Panchang.cloud is the **weekday-to-segment allocation**:

- Drik Panchanga-style: Sunday 14; Monday 9,12; Tuesday 2,5; Wednesday 12; Thursday 6; Friday 4,9; Saturday 1.
- B. V. Raman/supplied Muhurtha: Sunday 14; Monday 8,12; Tuesday 4,11; Wednesday 8; Thursday 12,13; Friday 4,8; Saturday 1,2.

This is a substantive computational difference, not merely a naming difference. The engine should therefore support both conventions and expose the selected method.

Regional practice can also differ in how strongly Durmuhurta is observed. Such practice differences should remain separate from the deterministic calculation itself.

## 9. Today's Calculation

`Dynamic Panchang calculation required.`

The engine should calculate local sunrise and sunset, derive the 15 daytime Muhurta intervals, apply the selected Durmuhurta convention, and return the exact local start/end times.

Recommended engine contract:

`durmuhurta(date, latitude, longitude, timezone, method="drik")`

where `method` is explicitly one of the supported traditions, rather than an implicit global setting.

## 10. Related Concepts

- Muhurta (मुहूर्त)
- Abhijit Muhurta (अभिजित् मुहूर्त)
- Rahu Kaal (राहु काल)
- Yamaganda (यमगण्ड)
- Gulika Kaal (गुलिक काल)
- Varjyam (वर्ज्यम्)
- Panchanga Shuddhi (पञ्चाङ्ग शुद्धि)

## 11. Knowledge-Base Summary

- **Canonical Name:** Durmuhurta (दुर्मुहूर्त)
- **Category:** Muhurtha / Daily Inauspicious Temporal Window
- **What it is:** A traditionally avoided daytime interval derived from the local daytime Muhurta divisions and weekday-specific rules.
- **Why it exists:** To identify periods traditionally avoided for selected important or auspicious commencements.
- **How it is determined:** Divide local daylight into 15 equal Muhurta intervals and apply the selected weekday-specific Durmuhurta allocation.
- **Primary traditional purpose:** Avoid selected major beginnings during an interval regarded as unfavourable.
- **Practical use:** Prefer another suitable time for major commencements when practical.
- **Important exceptions:** Routine, ongoing, review and unavoidable activities are not automatically prohibited.
- **Key variation:** Drik-style and B. V. Raman/supplied allocations differ and must be exposed as separate calculation methods.
- **Related concepts:** Muhurta, Abhijit Muhurta, Rahu Kaal, Yamaganda, Gulika Kaal, Varjyam.
- **Calculation-dependent:** Yes
- **Location-dependent:** Yes

## Provenance Note

The supplied source explicitly documents two Durmuhurta allocation systems. This knowledge page preserves that distinction rather than presenting one table as universally authoritative. The deterministic calculation is based on local sunrise/sunset and the selected weekday allocation. Traditional causal explanations are retained as interpretation and are not represented as established physical science.

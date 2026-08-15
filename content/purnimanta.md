---
id: panchang.purnimanta
canonical_term: Purnimanta
slug: purnimanta
category: calendar_system
aliases:
  - Purnimanta Masa
  - Pournimanta
  - पूर्णिमांत
  - पूर्णिमान्त
languages:
  - en
status: reviewed
last_reviewed: 2026-08-15
calculation:
  engine_key: masa.purnimanta
  dynamic: true
  location_sensitive: true
related_concepts:
  - panchang.masa
  - panchang.amanta
  - panchang.tithi
  - panchang.paksha
  - panchang.krishna_paksha
  - panchang.shukla_paksha
  - panchang.purnima
  - panchang.amavasya
---

# Purnimanta (पूर्णिमांत)

## What is it?

Purnimanta is a traditional system for reckoning the Hindu lunar month in which the lunar month ends with the completion of Purnima (Full Moon). The following day, Krishna Paksha Pratipada begins the next month.

Astronomically, the month boundary is associated with the Sun–Moon geocentric longitudinal separation reaching 180°, corresponding to opposition and the completion of the Purnima tithi.

A Purnimanta lunar month contains 30 tithis and averages about 29.53 solar days. Its two halves are arranged as Krishna Paksha followed by Shukla Paksha: Krishna Paksha follows the full-moon boundary and ends at Amavasya; Shukla Paksha begins after Amavasya and ends at the next Purnima boundary.

## Why does it exist?

Within the traditional calendrical framework, the lunar month provides a recurring unit for organizing tithis, pakshas, observances, festivals, and the selection of auspicious periods.

The supplied source associates this system with traditional ideas about changing solar-lunar influences and their relationship to human activity. Those explanations belong to the traditional interpretive framework and are not presented here as established physical mechanisms.

Purnimanta reckoning is particularly important for understanding regional calendar practice, especially in traditions where the month boundary is assigned to Purnima rather than Amavasya.

## How is it calculated?

The underlying astronomical inputs are the geocentric longitudes of the Sun and Moon.

The basic angular separation is:

`D = (Moon longitude - Sun longitude) mod 360°`

When `D = 180°`, the Purnima boundary is reached.

Under the Purnimanta month convention, the month ends at this Purnima boundary and the next day begins Krishna Paksha Pratipada of the next month.

The exact local clock time of the astronomical event depends on the observer's location and time zone. The specific regional rules for naming Purnimanta months are not sufficiently established by the supplied source material to define a complete independent naming algorithm here.

## How can a normal person use it?

A normal user mainly needs Purnimanta reckoning to understand why a lunar month can have a different name in one regional Panchang from another even though the underlying astronomical tithi sequence is the same.

The supplied material associates the following traditional practices with the lunar-month framework:

- Marriage: Magha, Phalguna, Vaishakha and Jyeshtha are presented as especially favourable months.
- Griha Pravesh: Krishna Paksha Pratipada is presented as favourable, with specified Shukla Paksha tithis also usable.
- Upanayanam: the early Krishna Paksha tithis, particularly Pratipada, Dwitiya and Tritiya, are presented as acceptable within the stated conditions.
- Tree felling: the waning phase is traditionally associated in the supplied material with obtaining strong and durable timber.

These are traditional electional rules, not guarantees of outcomes.

## Common misconceptions

### Purnimanta and Amanta are different astronomical lunar cycles

They are not different astronomical cycles. They are different conventions for assigning month boundaries and month names to the same underlying sequence of lunar phases and tithis.

### Krishna Paksha is always inauspicious

The supplied material explicitly rejects this as an absolute rule. Krishna Paksha contains activities for which particular tithis or phases are traditionally considered suitable, including the cited Griha Pravesh and Upanayanam cases.

### The Shukla Paksha itself changes between Amanta and Purnimanta

The underlying astronomical Shukla Paksha does not change. The principal difference between the month-reckoning systems is how the surrounding Krishna Paksha is assigned to month names.

## Important distinctions

### Purnimanta vs Amanta

Purnimanta months end at Purnima, while Amanta months end at Amavasya.

In Purnimanta reckoning, Krishna Paksha comes first within the named month and Shukla Paksha follows. In Amanta reckoning, Shukla Paksha comes first and Krishna Paksha follows.

### Lunar Masa vs Solar Masa

A lunar masa is organized around the synodic lunar cycle and tithis. A solar masa is organized around the Sun's movement from one zodiac sign to another, associated with Surya Sankramana.

### Purnima vs Purnimanta

Purnima is the lunar day/tithi associated with the full-moon opposition. Purnimanta is the month-reckoning convention that uses the completion of Purnima as the month boundary.

## Traditional interpretation

The supplied material describes traditional ideas in which changing Sun–Moon relationships are associated with changing environmental and human influences. It also presents a Raman-style interpretation involving cosmic radiation and electrical or biological effects.

Those statements are preserved as traditional interpretation. The astronomical/calculational fact is narrower: Purnimanta is a calendrical convention tied to the 180° Sun–Moon longitudinal separation and the completion of Purnima.

## Variations and disagreements

Regional practice can differ in how lunar months are named and which month-specific Muhurta rules are applied. The supplied material gives examples of regional disagreement around Ashadha marriage practice and special exceptions for Pushya and Chaitra under specified solar conditions.

The exact regional naming rules for Purnimanta month labels are not sufficiently established by the supplied source material to define them exhaustively here.

## Today's calculation

Dynamic Panchang calculation required.

The knowledge engine should supply:

- current lunar month under Purnimanta reckoning
- current Paksha
- current Tithi
- current Purnima boundary time where relevant
- location and timezone context

## Related concepts

- Masa
- Amanta
- Tithi
- Paksha
- Krishna Paksha
- Shukla Paksha
- Purnima
- Amavasya
- Surya Sankramana

## Knowledge-base summary

Canonical Name: Purnimanta (पूर्णिमांत)

Literal Meaning: A lunar month ending at Purnima.

Category: Lunar Month Reckoning System

What it is: A traditional convention in which the lunar month ends with the completion of Purnima and the next month begins with Krishna Paksha Pratipada.

Why it exists: To organize the lunar calendar, observances and traditional timing practices around a Purnima-based month boundary.

How it is determined: The astronomical boundary is associated with Sun–Moon geocentric longitudinal separation reaching 180°.

Primary traditional purpose: To assign lunar dates, festivals, observances and Muhurta rules to the appropriate lunar month under the Purnimanta convention.

Practical use: Understanding regional Panchang month names and applying month-specific traditional timing rules.

Important exceptions: Regional traditions and specific solar-position conditions can alter traditional Muhurta recommendations.

Common misconceptions: Purnimanta and Amanta do not represent different astronomical lunar cycles; they are different month-reckoning conventions.

Related concepts: Masa, Amanta, Tithi, Paksha, Krishna Paksha, Shukla Paksha, Purnima, Amavasya, Surya Sankramana.

Calculation-dependent: Yes

Location-dependent: Yes, because the exact astronomical boundary must be converted to local date and time.

---
id: panchang.paksha
canonical_term: Paksha
title: What Is Paksha? The Bright and Dark Fortnight of the Lunar Month
slug: paksha
category: calendar_cycle
aliases:
  - पक्ष
  - Shukla Paksha
  - शुक्ल पक्ष
  - Krishna Paksha
  - कृष्ण पक्ष
languages: [en, hi]
status: reviewed
last_reviewed: 2026-08-15
calculation:
  engine_key: paksha
  dynamic: true
  location_sensitive: true
related_concepts:
  - id: panchang.tithi
  - id: panchang.amavasya
  - id: panchang.purnima
  - id: panchang.chandrabala

# What is Paksha?

Paksha is one half of a lunar month in the Hindu calendrical system. It describes the two broad phases of the Moon's cycle: **Shukla Paksha**, the bright or waxing half, and **Krishna Paksha**, the dark or waning half.

A Paksha contains 15 Tithis and lasts approximately half of a synodic lunar month. The two halves meet at the major lunar markers of Purnima (full Moon) and Amavasya (new Moon).

## Why does Paksha exist?

In traditional Panchanga practice, Paksha provides a broad way of describing the Moon's changing phase and its place within the lunar month. Traditional Muhurta rules associate different activities with the waxing and waning halves and use Paksha together with Tithi, Nakshatra, Vara and other factors when assessing a time.

Traditional explanations may additionally attribute physiological, psychological or energetic effects to the changing lunar phase. Such explanations should be presented as **traditional interpretations**, not as established astronomical or medical facts.

## How is Paksha calculated?

Paksha is determined from the geocentric ecliptic longitudes of the Sun and Moon.

First calculate the normalized angular separation:

`D = (Moon longitude - Sun longitude) mod 360°`

- `0° <= D < 180°` → **Shukla Paksha**
- `180° <= D < 360°` → **Krishna Paksha**

The exact Tithi is determined from the same Sun-Moon separation using 12° divisions. Therefore Paksha can be understood as the larger 180° phase containing 15 Tithis.

## How can a normal person use Paksha?

Paksha should be treated as a **broad traditional filter**, not as a standalone decision rule.

Traditional Muhurta guidance may prefer Shukla Paksha for some constructive or growth-oriented activities, while particular activities may be permitted or preferred during Krishna Paksha. The applicable rule depends on the activity, Tithi, other Panchanga factors and the tradition being followed.

Examples from the supplied traditional material include:

- Marriage is generally given preference in Shukla Paksha, with specific traditions restricting the later Krishna Paksha period.
- Some house-entry and Samskara rules permit particular Tithis in Krishna Paksha.
- Traditional agricultural and forestry rules can assign specific uses to the waning phase.

The practical principle is therefore: **do not ask whether a Paksha is simply good or bad; ask whether the Paksha is appropriate for the activity under the relevant Muhurta rule.**

## Common misconceptions

### Krishna Paksha is completely inauspicious

Not necessarily. Traditional rules assign particular activities to Krishna Paksha and permit specific Tithis for certain Samskaras and other works.

### Shukla Paksha is automatically auspicious for every activity

No. Paksha is only one factor. Tithi, Nakshatra, Vara, Yoga, Karana and activity-specific Muhurta rules may change the assessment.

### Paksha and Tithi are the same thing

No. Paksha is the approximately 15-day half of the lunar month; Tithi is a 12° increment in Sun-Moon angular separation. A Paksha contains 15 Tithis.

### Paksha should be used as a medical rule

Traditional texts may associate lunar phases with bodily effects, but those claims should not be presented as medical advice or established scientific causation.

## Important distinctions

### Paksha vs Tithi

Paksha divides the lunar month into two broad phases. Tithi divides the Sun-Moon angular separation into 30 successive 12° segments.

### Shukla Paksha vs Krishna Paksha

Shukla Paksha is the waxing/bright half; Krishna Paksha is the waning/dark half.

### Paksha vs Chandrabala

Paksha describes the Moon's phase. Chandrabala is a separate Muhurta consideration concerning the Moon's strength relative to a person's birth constellation/rashi framework. They should not be conflated.

## Traditional interpretation

Traditional Hindu calendrical and Muhurta literature associates the waxing and waning phases with different classes of activity. The supplied material also describes Shukla Paksha in terms of growth and Krishna Paksha in terms of reduction, completion, cutting or dissolution.

These statements belong to the traditional interpretive layer. The astronomical layer is simpler: Paksha is a classification derived from the changing geocentric angular separation between the Sun and Moon.

## Variations and disagreements

Rules for the suitability of Krishna Paksha vary across traditions and specific activities. Some traditions apply stricter restrictions to auspicious ceremonies, while others permit particular early Krishna Paksha Tithis when additional conditions are satisfied.

Therefore the knowledge engine should preserve **tradition-specific rules** rather than encoding a universal rule that one Paksha is always auspicious and the other always inauspicious.

## Today's calculation

**Current result:** [dynamic Paksha, current Tithi, and transition time]

The runtime calculation should use the same astronomical inputs as Tithi calculation and expose the current Paksha together with the exact transition boundary.

## Related concepts

- [Tithi]
- [Amavasya]
- [Purnima]
- [Chandrabala]
- [Panchang]
- [Muhurta]

## Knowledge-base summary

- **Canonical Name:** Paksha (पक्ष)
- **Literal Meaning:** Half/fortnight of a lunar month
- **Category:** Panchanga/calendar division
- **What it is:** A 180° phase of the Sun-Moon geocentric angular separation, classified as Shukla or Krishna Paksha.
- **Why it exists:** A traditional framework for describing the broad lunar phase and applying activity-specific calendrical and Muhurta rules.
- **How it is determined:** Normalize Moon longitude minus Sun longitude and classify the result below or above 180°.
- **Primary traditional purpose:** Provide a broad phase-level filter for interpreting lunar time in calendrical observances and Muhurta.
- **Practical use:** Use as one factor alongside Tithi and the other Panchanga/Muhurta conditions.
- **Important exception:** Krishna Paksha is not universally prohibited; suitability depends on the activity and tradition.
- **Common misconception:** A Paksha is not intrinsically good or bad for every possible activity.
- **Related concepts:** Tithi, Amavasya, Purnima, Chandrabala.
- **Calculation-dependent:** Yes
- **Location-sensitive:** Yes, because the displayed current state and transition times depend on the local time/location context.

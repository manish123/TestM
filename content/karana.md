---
id: panchang.karana
canonical_term: Karana
title: What Is Karana? The Half-Tithi Division in Panchang
slug: karana
category: anga
aliases:
  - करण
  - Karana
  - Vishti Karana
  - Bhadra
languages: [en]
status: reviewed
last_reviewed: 2026-08-15
calculation:
  engine_key: karana
  dynamic: true
  location_sensitive: true
related_concepts:
  - id: panchang.panchang
  - id: panchang.tithi
  - id: panchang.yoga
  - id: panchang.nakshatra
  - id: panchang.vara
  - id: panchang.panchanga-shuddhi
---

# What is Karana?

Karana is the fifth limb of Panchang and, mathematically, one half of a Tithi. A Tithi spans 12° of angular separation between the Sun and Moon; a Karana spans 6°.

The Sanskrit term *Karana* is traditionally associated with a means or instrument by which an action is accomplished. In Muhurta practice, Karana is therefore treated as a finer-grained Panchanga factor for judging the suitability of an activity.

## The 11 Karanas

Panchang recognizes 11 Karana names divided into two groups.

### Movable / recurring Karanas

Seven Karanas recur through most of the lunar month:

1. Bava (बव)
2. Balava (बालव)
3. Kaulava (कौलव)
4. Taitula (तैतिल)
5. Garija (गर)
6. Vanija (वणिज)
7. Vishti (विष्टि), commonly called Bhadra (भद्रा)

These seven repeat in their prescribed cyclic sequence.

### Fixed Karanas

Four Karanas occur at fixed positions in the lunar-month sequence:

8. Sakuni (शकुनि)
9. Chatushpada (चतुष्पद)
10. Naga (नाग)
11. Kimstughna (किंस्तुघ्न)

Kimstughna occurs at the beginning of the recurring sequence, while Sakuni, Chatushpada and Naga occur at the specified end-of-month positions.

## Why does Karana exist?

From the traditional Muhurta perspective, Karana provides a finer subdivision of the lunar day than Tithi alone. Traditional rules assign different characteristics to different Karanas and use those characteristics when matching a time to the nature of an intended action.

The traditional material associates Karana with the practical or action-oriented quality of a Muhurta. These are traditional interpretive principles, not established scientific mechanisms.

## How is Karana calculated?

The calculation is based on the angular separation between the Moon and Sun.

The basic angular separation is:

`Moon longitude − Sun longitude`

If the result is negative, 360° is added so that the separation lies within the 0°–360° cycle.

Each Karana occupies 6° (360 arc-minutes). The position within the 360° cycle therefore identifies the corresponding half-Tithi interval.

A production Panchang engine should calculate the exact transition using the underlying solar and lunar longitudes and their changing rates of motion, rather than treating every Karana as a fixed clock duration.

## Karana sequence

The sequence is not simply 11 names repeated in numerical order.

Kimstughna occupies the first half of Shukla Pratipada. The seven recurring Karanas then proceed cyclically through the lunar month. At the end of the cycle, the four fixed Karanas—Sakuni, Chatushpada, Naga and Kimstughna—occur at their prescribed positions.

This distinction is important for implementation because a Karana engine needs both the angular calculation and the canonical sequence rules.

## How should a normal person use Karana?

Karana should normally be treated as one factor within Panchanga rather than as an isolated decision rule.

Traditional Muhurta guidance associates particular Karanas with particular types of activity. Examples from the supplied tradition include:

- **Bava:** traditionally favorable for activities of lasting or permanent importance.
- **Taitula:** traditionally favorable for marriage and other auspicious ceremonies.
- **Vishti / Bhadra:** generally avoided for ordinary auspicious activities, while traditionally considered suitable for forceful, competitive, adversarial or difficult actions.
- **Sakuni:** traditionally associated with particular forms of mantra practice and ritual activity.

The practical rule for Panchang.cloud should therefore be: show the current Karana, its exact local start and end time, its traditional classification, and the types of activities for which the tradition considers it suitable or unsuitable.

## Vishti Karana and Bhadra

Vishti is the formal Karana name. Bhadra is the commonly used traditional name for the period in which Vishti Karana operates.

They should not be represented as two separate Panchanga limbs or two separate Karana types.

## Common misconceptions

### Karana and Tithi are the same thing

No. A Tithi represents a 12° increment of Sun-Moon angular separation; a Karana represents a 6° increment and is therefore half of a Tithi.

### Vishti / Bhadra is always bad

Traditional Muhurta rules do not treat Vishti as universally unsuitable. It is generally avoided for ordinary auspicious works, but traditions associate it with forceful, competitive, adversarial or difficult activities.

### Every Karana occurs only once

No. Seven Karanas recur repeatedly through the lunar month, while four are fixed in the lunar-month sequence.

### Karana alone decides whether an activity is auspicious

No. Karana is one Panchanga factor. Depending on the activity, Tithi, Vara, Nakshatra, Yoga, Muhurta rules and other conditions may also need to be considered.

## Important distinctions

### Karana vs Tithi

Tithi = 12° of Sun-Moon angular separation.

Karana = 6° of Sun-Moon angular separation.

Each Tithi therefore contains two Karana intervals.

### Vishti vs Bhadra

Vishti is the Karana's formal name. Bhadra is the traditional/common name used for the Vishti period.

### Karana vs special Muhurta Yogas

Karana is a permanent component of the Panchanga calculation. Special combinations such as Siddha Yoga are formed from other calendrical conditions and should not be conflated with the Karana itself.

## Traditional interpretation

The supplied traditional material explains Karana through the broader Muhurta framework of selecting a time whose qualities are appropriate to the intended action. It associates different Karanas with different classes of activity.

Claims that these effects are caused by electromagnetic radiation, animal magnetism, biological radiation or other physical mechanisms should be presented as historical/traditional interpretations, not as established astronomical or scientific conclusions.

## Variations and disagreements

Traditional practice can differ in how strongly particular Karanas are emphasized and in which activities are assigned to them. The knowledge base should preserve such differences where they materially affect practice rather than presenting one regional interpretation as universally authoritative.

## Today's calculation

**Current result:** [dynamic Karana, start time and end time]

The displayed result must be calculated from the Panchang engine for the user's selected location and local date/time.

## Knowledge-base summary

- **Canonical Name:** Karana (करण)
- **Category:** Panchanga limb
- **Meaning:** A half-Tithi division used as a finer-grained Panchanga factor.
- **Astronomical basis:** 6° of Sun-Moon angular separation.
- **Number of names:** 11
- **Recurring Karanas:** Bava, Balava, Kaulava, Taitula, Garija, Vanija and Vishti.
- **Fixed Karanas:** Sakuni, Chatushpada, Naga and Kimstughna.
- **Primary traditional purpose:** Judging the suitability of a time for particular classes of activity within Muhurta.
- **Important practical distinction:** Vishti is commonly called Bhadra.
- **Calculation-dependent:** Yes.
- **Location-dependent:** The underlying planetary positions are time-dependent; the displayed Karana transition and clock times must be localized to the user's location and timezone.
- **Related concepts:** Tithi, Vara, Nakshatra, Yoga, Panchanga Shuddhi, Vishti/Bhadra.

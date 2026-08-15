---
id: panchang.yoga
canonical_term: Yoga
title: What Is Yoga? Understanding Nitya Yoga in Panchang
slug: yoga
category: anga
aliases:
  - Nitya Yoga
  - Panchanga Yoga
  - नित्य योग
  - योग
languages: [en, hi]
status: reviewed
last_reviewed: 2026-08-15
calculation:
  engine_key: yoga
  dynamic: true
  location_sensitive: true
related_concepts:
  - id: panchang.panchang
  - id: panchang.tithi
  - id: panchang.vara
  - id: panchang.nakshatra
  - id: panchang.karana
  - id: panchang.siddha-yoga
  - id: panchang.panchanga-shuddhi
---

# What is Yoga?

In Panchang, **Yoga (नित्य योग)** is the fourth of the five Panchanga limbs. It is a calendrical quantity derived from the combined apparent geocentric longitudes of the Sun and Moon.

The combined longitude is divided into 27 equal sectors of **13°20′ (800 arc-minutes)**. The sector currently occupied by the Sun-Moon sum determines the Nitya Yoga operating at that time.

The term *Yoga* comes from the Sanskrit root *yuj*, associated with joining or combining. In this Panchanga context, it refers to the mathematical combination of the solar and lunar longitudes.

There are **27 Nitya Yogas**, each traditionally associated with a name, character and set of applications. Examples include Vishkambha, Priti, Sukarma, Atiganda, Shula, Ganda, Vyatipata and Vaidhrti.

## Why does Yoga exist?

Traditional Muhurtha practice uses Nitya Yoga as one component of Panchanga Shuddhi: the assessment of whether the five Panchanga limbs are suitable for a proposed activity.

Traditional interpretations associate the different Yogas with varying qualities and prescribe some for auspicious activities while avoiding others. The supplied classical framework describes the solar and lunar combination through traditional ideas concerning subtle influences, vitality and health.

These explanations belong to the traditional interpretive framework. Astronomically, Nitya Yoga is a mathematical measure derived from the apparent positions of the Sun and Moon.

## How is Yoga calculated?

The required inputs are:

1. The Sun's apparent geocentric ecliptic longitude.
2. The Moon's apparent geocentric ecliptic longitude.

The combined longitude is:

**Sun longitude + Moon longitude**

If the sum exceeds 360°, 360° is subtracted as required to bring it into the 0°–360° range.

The resulting angular value is divided into 27 sectors of 13°20′ (800 arc-minutes).

In arc-minutes:

**Yoga index = floor((Sun longitude + Moon longitude) / 800′) + 1**

with the combined longitude reduced modulo 360° before the division.

The remainder indicates how much of the current Yoga has elapsed. Subtracting the remainder from 800′ gives the remaining angular portion.

To estimate the ending time, the remaining angular portion is related to the combined daily motion of the Sun and Moon. In an operational Panchang engine, the exact transition should be determined from the underlying astronomical positions rather than assuming constant daily motion.

### Worked example

Suppose:

- Sun longitude = 114°40′
- Moon longitude = 326°00′

Combined longitude:

114°40′ + 326°00′ = 440°40′

Reducing by 360°:

80°40′

In arc-minutes:

(80 × 60) + 40 = 4,840′

Then:

4,840 ÷ 800 = 6 remainder 40′

Therefore six complete Yoga sectors have elapsed and the **7th Yoga, Sukarma**, is operating. The current Yoga has 40′ elapsed and 760′ remaining.

The supplied source example uses assumed daily motions of approximately 0°57′ for the Sun and 11°47′ for the Moon, giving a combined daily motion of 12°44′ (764′), and derives approximately 23 hours 50 minutes to the Yoga transition from the stated reference time.

## How can a normal person use Yoga?

A normal user does not need to perform the calculation manually. Panchang.cloud should calculate the current Yoga and its local transition time and explain its traditional practical classification.

For general auspicious activities, the supplied Muhurtha framework identifies the following Yogas as particularly important to avoid:

- **Atiganda** — 6th
- **Shula** — 9th
- **Ganda** — 10th
- **Vyatipata** — 17th
- **Vaidhrti** — 27th

For marriage Muhurtha, the traditional rules supplied here are more restrictive and include Vyatipata, Dhruva, Mrityu, Ganda, Vajra, Shula, Vishkambha, Atiganda, Vyaghata and Parigha among the Yogas to avoid.

The practical principle is not that a Yoga is universally "good" or "bad". Its suitability depends on the activity being undertaken and on the wider Muhurtha assessment.

## Important exceptions

The supplied Muhurtha material identifies a specific exception for **Vyatipata and Vaidhrti**: their associated defect is described as becoming inactive after midday, allowing their use in certain circumstances after noon.

This should be presented as a traditional Muhurtha rule, not as a universal astronomical or scientific fact.

The material also distinguishes between ordinary worldly activities and spiritual practices. Some periods regarded as unsuitable for material activities may traditionally be considered appropriate for initiation, meditation or mantra practice.

## Common misconceptions

### Vyatipata and Vaidhrti are equally inauspicious for the entire day

Traditional Muhurtha rules cited here state that their associated defect becomes inactive after midday.

### A Nitya Yoga is the same as Siddha Yoga

No. **Nitya Yoga** is one of the five Panchanga limbs and is calculated directly from the combined longitudes of the Sun and Moon.

Other Muhurtha combinations such as Siddha Yoga, Amrita Siddha Yoga and Mahendra Yoga arise from combinations involving factors such as Vara, Tithi and Nakshatra. They are separate concepts.

### A difficult Nitya Yoga means the entire day is unusable

No. Traditional Muhurtha is contextual. The suitability of a time depends on the activity, the other Panchanga limbs and the applicable exceptions and rules.

### Nitya Yoga is a permanent condition in a birth chart

No. Nitya Yoga is a time-dependent Panchanga calculation. It changes as the Sun-Moon combined longitude crosses successive 13°20′ sectors.

## Important distinctions

### Nitya Yoga vs. Muhurtha/Special Yogas

**Nitya Yoga:** one of the five Panchanga limbs; calculated from Sun + Moon longitude and divided into 27 equal sectors.

**Siddha and other special Muhurtha Yogas:** combinations formed from other Panchanga factors such as Vara, Tithi and Nakshatra. They are independent of the Nitya Yoga calculation.

### Yoga vs. Tithi

Tithi is based on the angular separation between the Sun and Moon. Nitya Yoga is based on the sum of their longitudes.

### Yoga vs. Nakshatra

Nakshatra is determined from the Moon's position along the ecliptic. Nitya Yoga is determined from the combined Sun-Moon longitude.

## Traditional interpretation

Traditional Muhurtha literature assigns different qualities and uses to the 27 Nitya Yogas. Some are considered supportive of auspicious activity, while others are traditionally avoided for particular undertakings.

The supplied B. V. Raman-based material also interprets these combinations through traditional ideas concerning solar and lunar influences, vitality and biological rhythms. These are traditional interpretations rather than established astronomical or medical mechanisms.

Astronomically, the underlying calculation is an angular measure derived from the apparent geocentric ecliptic longitudes of the Sun and Moon.

## Variations and disagreements

Traditional practice is not completely uniform in how every Yoga should be treated. The supplied material notes that some authorities distinguish between the initial portion of certain prohibited Yogas and the remainder of the period, whereas a conservative Muhurtha approach may avoid the entire Yoga for highly consequential activities such as marriage.

Where traditions disagree, Panchang.cloud should identify the rule as a tradition-specific interpretation rather than presenting one school as an uncontested universal rule.

## Today's calculation

**Current result:** [dynamic Nitya Yoga and local start/end time]

The result must be generated by the Panchang calculation engine from the astronomical positions for the user's location and date.

## Related concepts

- [Panchang]
- [Tithi]
- [Vara]
- [Nakshatra]
- [Karana]
- [Siddha Yoga]
- [Panchanga Shuddhi]
- [Mahapatha Dosha]

## Knowledge-base summary

- **Canonical Name:** Yoga / Nitya Yoga (योग / नित्य योग)
- **Category:** Panchanga Limb
- **What it is:** A 13°20′ (800 arc-minute) sector derived from the combined apparent geocentric longitudes of the Sun and Moon.
- **Why it exists:** In traditional Panchanga and Muhurtha practice, it provides one measure for assessing the suitability of a time for different activities.
- **How it is determined:** Sun longitude + Moon longitude, reduced to 0°–360°, divided into 27 sectors of 13°20′.
- **Primary traditional purpose:** To distinguish traditionally favourable and unfavourable periods for different activities as part of Panchanga Shuddhi.
- **Practical use:** Check the current Yoga, its local transition time and the traditional rule applicable to the intended activity.
- **Important exception:** Traditional material supplied here states that the Vyatipata and Vaidhrti defect becomes inactive after midday.
- **Common misconceptions:** Nitya Yoga is not the same as Siddha Yoga; a difficult Yoga does not automatically make an entire day unusable.
- **Related concepts:** Tithi, Vara, Nakshatra, Karana, Siddha Yoga, Panchanga Shuddhi.
- **Calculation-dependent:** Yes.
- **Location-sensitive:** Yes, because the displayed transition time depends on the local time representation of the astronomical calculation.
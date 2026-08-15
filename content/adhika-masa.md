---
id: panchang.adhika_masa
canonical_term: Adhika Masa
title: What Is Adhika Masa? Meaning, Calculation and Traditional Use
slug: adhika-masa
category: masa
aliases:
  - Adhik Maas
  - Adhika Masa
  - Mala Masa
  - Purushottama Masa
  - अधिक मास
  - अधिकमास
languages: [hi, en]
status: established
last_reviewed: 2026-08-15
calculation:
  engine_key: adhika_masa
  dynamic: true
  location_sensitive: true
related_concepts:
  - Masa
  - Amanta
  - Purnimanta
  - Tithi
  - Surya Sankramana
  - Kshaya Masa
sources:
  - name: B. V. Raman — Muhurtha (Electional Astrology)
    type: supplied-source
    note: Raman source does not provide the complete Adhika Masa treatment.
  - name: S. B. Dikshit / The Indian Calendar tradition
    type: calendrical-reference
    note: Intercalation and Sankranti-based month reckoning.
---

# Adhika Masa (अधिक मास)

## 1. What Is It?

**Adhika Masa** is an intercalary lunar month used in the Hindu lunisolar calendar to keep the lunar calendar aligned with the solar year and the seasons.

A lunar month is about 29.5 days, while the Sun takes roughly a month to traverse a zodiac sign. Because the lunar year is shorter than the solar year, an additional lunar month is periodically required.

The defining calendrical rule is:

> **If a lunar month contains no Surya Sankranti — no transit of the Sun from one sidereal zodiac sign to the next — that lunar month is designated Adhika.**

Under the Amanta system, the Adhika month takes the name of the following regular month. The corresponding Purnimanta treatment follows the applicable month-reckoning convention.

Adhika Masa occurs approximately every 32–33 months, but it is not a fixed three-year cycle.

## 2. Why Does It Exist?

Its primary calendrical purpose is **intercalation**: preventing the lunar calendar from drifting progressively through the solar seasons.

Without intercalation, the approximately 11-day annual difference between a 12-lunar-month year and the solar year would accumulate until lunar months and seasonal markers became progressively misaligned.

Traditional Hindu practice also gives Adhika Masa a distinct religious character. It is widely associated with **Purushottama Masa**, particularly with Vishnu devotion, japa, dana, vrata and other spiritual practices. These ritual interpretations belong to the traditional religious layer rather than the astronomical definition.

## 3. How Is It Calculated or Determined?

The production calculation is based on the relationship between lunar-month boundaries and solar Sankranti events.

For an Amanta implementation:

1. Determine consecutive Amavasya instants.
2. Define the lunar month between those boundaries.
3. Determine all sidereal Surya Sankranti events inside that lunar-month interval.
4. If **zero Sankrantis** occur inside the interval, classify that lunar month as **Adhika**.
5. Assign its month name according to the applicable calendrical naming convention, normally the name of the following regular month in the Amanta framework.

This is therefore a deterministic astronomical/calendar-engine rule, not a fixed annual date rule.

Because Sankranti and Amavasya are instantaneous astronomical events, the local civil date/time can vary with location and timezone.

## 4. How Can a Normal Person Use It?

For ordinary Panchang use, the important question is first to know whether the current lunar month is **Adhika** or **Nija/Shuddha** (regular).

Traditional practice commonly distinguishes between:

- **Spiritual and devotional activity:** generally encouraged during Adhika Masa; japa, dana, vrata and Vishnu worship are particularly associated with it.
- **Permanent auspicious Samskaras and major ceremonies:** many traditional authorities generally avoid initiating such rites during Adhika Masa, although exact rules vary by tradition and by the type of activity.

Therefore Panchang.cloud should not simply label the entire month "bad." Adhika Masa has a strong positive ritual identity for spiritual practice while being treated cautiously for many permanent worldly ceremonies.

## 5. Common Misconceptions

### Adhika Masa occurs exactly every three years

Not exactly. It occurs periodically because of the accumulated lunar-solar difference, averaging roughly once every 32–33 months.

### Adhika Masa is an astronomical error or an abnormal lunar month

No. It is an intentional **intercalation mechanism** in a lunisolar calendar.

### Adhika Masa is universally inauspicious

That is too broad. Traditional practice often restricts certain permanent auspicious ceremonies while specifically encouraging spiritual disciplines and devotional activity.

### Adhika Masa changes the underlying tithis

No. The astronomical tithi cycle continues normally. Adhika Masa changes the **month classification/name**, not the fundamental tithi calculation.

## 6. Important Distinctions

### Adhika Masa vs Nija/Shuddha Masa

Adhika is the intercalated occurrence; Nija or Shuddha is the regular occurrence of the corresponding month.

### Adhika Masa vs Amanta/Purnimanta

Amanta and Purnimanta determine where the lunar month boundary is placed. Adhika determines whether a lunar month contains a solar Sankranti and therefore receives intercalary status. These are different layers of the calendar model.

### Adhika Masa vs Kshaya Masa

- **Adhika:** zero Sankrantis in one lunar month; a month is inserted/repeated.
- **Kshaya:** two Sankrantis in one lunar month; a month name is effectively skipped/expunged.

## 7. Traditional Interpretation

Traditional Hindu practice gives Adhika Masa special religious significance, especially as Purushottama Masa in Vaishnava traditions. Japa, dana, vrata, worship and other spiritual disciplines are commonly associated with the period.

Claims about physical or electromagnetic effects should not be presented as scientific facts unless independently demonstrated. They belong, if used, in a clearly labelled traditional-interpretation layer.

## 8. Variations and Disagreements

Regional calendars can differ in month-reckoning conventions and in the detailed ritual rules applied during Adhika Masa.

The astronomical trigger — a lunar month without a Sankranti — is the core calendrical criterion. Ritual restrictions and prescriptions are more tradition-dependent.

## 9. Today's Calculation

`Dynamic Panchang calculation required.`

The engine should calculate the current lunar-month interval, detect Sankranti events within it, classify the month as Adhika or regular, and expose the result using the selected Amanta/Purnimanta convention.

## 10. Related Concepts

- Masa (मास)
- Amanta (अमांत)
- Purnimanta (पूर्णिमांत)
- Tithi (तिथि)
- Amavasya (अमावस्या)
- Surya Sankramana (सूर्य संक्रांति)
- Kshaya Masa (क्षय मास)
- Purushottama Masa (पुरुषोत्तम मास)

## 11. Knowledge-Base Summary

- **Canonical Name:** Adhika Masa (अधिक मास)
- **Aliases:** Adhik Maas, Mala Masa, Purushottama Masa
- **Category:** Lunar Month / Intercalation
- **What it is:** An intercalary lunar month inserted to reconcile lunar and solar calendars.
- **Why it exists:** To prevent the lunar calendar from drifting through the solar seasons.
- **How it is determined:** A lunar month containing no Surya Sankranti is classified as Adhika.
- **Primary traditional purpose:** Calendar intercalation; traditionally also a period especially associated with spiritual practice.
- **Practical use:** Identify the intercalary month and apply the applicable regional/traditional rules for ceremonies and spiritual observances.
- **Important exceptions:** Ritual restrictions vary by tradition; Adhika Masa should not be described as universally inauspicious.
- **Common misconceptions:** It is not exactly a fixed three-year event and does not alter the underlying tithi cycle.
- **Related concepts:** Masa, Amanta, Purnimanta, Tithi, Surya Sankramana, Kshaya Masa.
- **Calculation-dependent:** Yes
- **Location-dependent:** Yes

## Provenance Note

The supplied B. V. Raman material did not fully cover Adhika Masa. The astronomical/calendar definition and intercalation logic are therefore supplemented from established Indian calendrical references. Source provenance is retained so the knowledge engine can distinguish source-derived material from broader established Panchanga knowledge.

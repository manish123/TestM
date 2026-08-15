# Panchang Knowledge Base

This repository defines the content model and editorial specification for the Panchang.cloud Knowledge Base.

The Knowledge Base is intended to make Panchang understandable and practically usable: not merely to report a time, but to explain what the concept means, why it exists, how it is determined, how it has traditionally been interpreted, and how a person can use it responsibly.

## Current scope

This repository contains content and templates only. The Panchang.cloud rendering/knowledge engine will be designed after the content model has been validated.

## Canonical content structure

Every knowledge concept follows the same core sequence:

1. What is it?
2. Why does it exist?
3. How is it calculated?
4. Traditional interpretation
5. How to use it
6. Common misconceptions
7. Today's calculation
8. Sources
9. Related concepts

## Editorial principles

- Distinguish traditional claims from astronomical/calendrical computation and practical guidance.
- Do not present traditional interpretations as scientific causation.
- Prefer identifiable primary/classical sources and clearly identify the source tradition where relevant.
- Explain the calculation rather than treating the Panchang output as a black box.
- Connect concepts to current, location-aware Panchang calculations where applicable.
- Avoid content written solely to target search keywords.
- One canonical knowledge entity should absorb aliases and synonymous search terms rather than creating duplicate articles.
- Current dates and times belong to the calculation engine, not hard-coded article content.

## Repository structure

```text
schema/
  knowledge-schema.yaml
  knowledge-index.yaml

templates/
  knowledge-template.md

content/
  panchang.md
  tithi.md
  vara.md
  nakshatra.md
  yoga.md
  karana.md
  muhurta.md
  rahu-kaal.md
  abhijit-muhurta.md
  yamaganda.md
  gulika-kaal.md
  choghadiya.md
  ekadashi.md
  purnima.md
  amavasya.md
```

## Initial knowledge graph

The first complete graph contains 15 canonical entities spanning three major areas:

### Core Panchanga

- Panchang
- Tithi
- Vara
- Nakshatra
- Yoga
- Karana

### Muhurta and timing

- Muhurta
- Rahu Kaal
- Abhijit Muhurta
- Yamaganda
- Gulika Kaal
- Choghadiya

### Vrat and lunar observances

- Ekadashi
- Purnima
- Amavasya

`schema/knowledge-index.yaml` is the canonical dependency/relationship index. Its validation section currently has an expected entity count of 15 and zero unresolved entity IDs.

## Next phase

The next implementation step is the Panchang.cloud Knowledge Engine. It should consume this content contract and entity graph, render the Markdown knowledge into crawlable HTML pages, resolve canonical internal links, inject location-aware current Panchang calculations, and generate appropriate metadata and sitemap entries.

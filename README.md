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
- Prefer primary/classical sources and clearly identify the source tradition where relevant.
- Explain the calculation rather than treating the Panchang output as a black box.
- Connect concepts to current, location-aware Panchang calculations where applicable.
- Avoid content written solely to target search keywords.
- One canonical knowledge entity should absorb aliases and synonymous search terms rather than creating duplicate articles.

## Repository structure

```text
schema/
  knowledge-schema.yaml

templates/
  knowledge-template.md

content/
  panchang.md
  tithi.md
  rahu-kaal.md
```

## Initial validation corpus

The first three concepts deliberately cover different knowledge types:

- Panchang — umbrella/calendar concept
- Tithi — calendrical/astronomical concept
- Rahu Kaal — practical timing concept

The template will be expanded only after these concepts demonstrate that the content model works across different types of Panchang knowledge.

---
id: panchang.<concept_id>
canonical_term: <Canonical Term>
title: <Human-readable title>
slug: <canonical-slug>
category: <category>
aliases:
  - <alias>
languages:
  - en
status: draft
last_reviewed: YYYY-MM-DD
seo:
  title: <optional search title override>
  description: <unique human-readable search/social description>
  og_image: <optional image path>
  noindex: false
calculation:
  engine_key: <engine key or null>
  dynamic: true
  location_sensitive: true
related_concepts:
  - panchang.<canonical_entity_id>
sources:
  - name: <source name>
    type: <classical|astronomical|methodology|other>
    citation: <bibliographic citation>
    locator: <chapter/section/page if available>
---

# <Canonical Term>

## What is it?

Define the concept clearly in plain language. State what it is before discussing interpretation or practice.

## Why does it exist?

Explain the calendrical, astronomical, traditional, or practical reason the concept exists. Distinguish historical/traditional rationale from modern explanation where necessary.

## How is it calculated?

Explain the underlying calculation or determination method. Where the result depends on location, date, sunrise, sunset, astronomical position, timezone, or another Panchang parameter, say so explicitly.

## Traditional interpretation

Describe the relevant traditional interpretation and observance. Attribute claims to the relevant tradition or source where possible. Do not convert traditional interpretation into unsupported scientific causation.

## How should it be used?

Give practical guidance for someone using Panchang. Explain what the concept is useful for, what it does not decide, and any important qualifications.

## Common misconceptions

Address the most likely misunderstandings, especially interpretations that are overly absolute or confuse calculation with tradition.

## Today's calculation

This section is intentionally dynamic. The eventual Panchang.cloud knowledge engine will insert the current location-aware calculation here rather than storing a date/time in the Markdown content.

**Current result:** [dynamic Panchang calculation]

**See today's Panchang:** [dynamic link]

## Sources

List identifiable sources used for the definition, tradition, calculation, or methodology. Keep source types distinct where useful.

## Related concepts

Use canonical entity IDs from `schema/knowledge-index.yaml`. The engine resolves IDs to titles, slugs and internal links.

## SEO notes

Do not add `meta keywords`. SEO metadata belongs in frontmatter and is converted by the static builder into HTML `<title>`, `<meta name="description">`, canonical, Open Graph/social metadata, robots directives where explicitly required, and supported structured data. The article body remains the primary source of useful search content.

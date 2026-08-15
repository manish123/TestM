# Knowledge Base migration utilities

These utilities are temporary repository-maintenance tools for bringing the existing Markdown corpus into the v1.1 content contract before the static knowledge engine is introduced.

The migration target is:

- `related_concepts` contains canonical `panchang.*` entity IDs only.
- `category` uses the schema enum.
- every content file has YAML frontmatter with the required identity fields.
- publishable status is one of `draft`, `established`, `reviewed`, `published`, `deprecated`.
- SEO metadata, when present, lives in frontmatter rather than the article body.

Do not put calculation logic in these utilities. They only normalize content metadata.

The final engine should still validate the resulting corpus rather than silently accepting unresolved references.

# Halcyon Labs — Items Showcase

This repository holds the source content for the public items showcase.

Every item is a Markdown file under `content/items/`.  The YAML front matter
records the item title, its publication state via `published`, and an optional
`link` pointing at the item's companion code repository.

## Publishing notes

- Items with `published: true` are rendered on the public site.
- Items with `published: false` are drafts and are not rendered.
- The `link` field, when present, must point to a companion repository that has
  actually shipped its implementation.

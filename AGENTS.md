# Editing Guide (humans and AI agents)

1. **One entity per file**, named in lowercase kebab-case, e.g. `objects/silver-key.md`.
2. **Start from a template** in `templates/`. Keep the front matter fields; fill unknowns with `Unknown`, never invent canon.
3. **Link pages** with relative Markdown links, e.g. `[Silver Key](../objects/silver-key.md)`.
4. **Register every new page** in `index.md` under the right section, alphabetically.
5. **Ranks and levels** must use the scales defined in `rank-scale.md`. Propose changes to the scale in a separate commit.
6. **Do not delete** pages or facts. Mark outdated information with `~~strikethrough~~` and add a dated note, or set `status: deprecated` in front matter.
7. **Canon status**: every page has `status: draft | canon | deprecated`. Only the owner (Legion) promotes a page to `canon`.
8. **Commit messages**: short and specific, e.g. `Add character: Elena Voss`.
9. Keep spoilers in a `## Spoilers` section at the bottom of a page.

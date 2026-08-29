# AGENTS.md

Awesome A2A is a curated list of A2A-protocol-compatible agents, tools, and libraries. It is pure Markdown: there is no code, build, test, or lint step, and no CI. Every change is an edit to `README.md` - the entire project. The "build" is Markdown that renders cleanly on GitHub and follows the conventions below.

## Repo layout

- `README.md` - the whole project; single source of truth. `AGENTS.md` complements it, it does not duplicate it.
- `LICENSE` - Apache-2.0.

## Adding an entry (the only real task)

Changes land via fork + PR to `main`. To add an entry:

1. Place it in the correct major section (Agents / Tools & Libraries / Documentation & Resources / Examples & Tutorials) and the correct subheading (e.g. Agents > "Browser & Web"). Read the existing sections before choosing.
2. Use the exact entry format:

   `- **[Name](https://github.com/owner/repo)** \`Language\` \`License\` - Brief description of what it does and its key capabilities.`

3. Update the stats line in the header: `_8 agents · 20 tools & libraries · 4 docs · 2 examples · Last updated 2026-05-25_`. Bump the count for the section you touched and the date.
4. Keep the `<p align="right"><a href="#-contents">↑ Back to top</a></p>` footer after each major section.

## Conventions

- Tags: `⭐ Featured` is applied by curators only - never self-apply. `🆕 New` marks entries added in the last ~90 days.
- Use plain hyphens in prose, not em dashes (a prior commit replaced every em dash).
- Entries are external links only: no local files, no images beyond the header badges.
- Keep descriptions factual and specific (what it does, key capabilities); one bullet per entry.
- Headings use emoji and their GitHub-generated anchors; keep heading text stable or update the Contents links in the same change.
- One entry per PR, with a brief explanation of what is being added.

## Quality gates (from the README's Contributing section)

Only accept submissions that follow the A2A protocol spec, ship comprehensive docs, include working examples or demos, are actively maintained, handle errors properly, and follow security best practices. Verify the linked repo exists and actually speaks A2A before adding it.

## History

Recent work has been documentation-only: restructuring README sections, adding the official a2aproject SDKs, and adding inference-gateway ecosystem projects. Keep the diff limited to `README.md` unless a task explicitly asks for more.

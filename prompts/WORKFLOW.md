# Book Creation Workflow

## Folder and file convention

Each book has a lowercase, hyphenated ID and its own folder under the most suitable category:

```text
books/
├── prophets/<book-id>/
├── prophet-muhammad/<book-id>/
├── companions/<book-id>/
└── everyday-islam/<book-id>/
    ├── README.md
    ├── outline.md
    ├── sources.md
    ├── progress.md
    └── sections/
        ├── 01-short-title.md
        └── 02-short-title.md
```

Do not create empty placeholder files for every proposed book. Create a book folder when its skeleton is researched, so the repository does not imply that unresearched books are already underway.

## First run: create the skeleton only

When a book is selected for the first time:

1. Inspect the shared guidelines and catalogue.
2. Research the subject online. Begin with Qur'an passages or specific hadith references, then inspect reputable scholarly context.
3. Build a source register. Connect each planned section to specific references.
4. Draft `outline.md` with a coherent, source-backed sequence. List section titles, one main event, a proposed value, and references.
5. Draft `README.md` with title, ID, audience, scope, reading guidance, and links to the other book files.
6. Draft `sources.md` with claims, source references, URLs, access dates, and notes on authenticity/limitations.
7. Draft `progress.md` with all sections marked `Planned`, and no section marked written.
8. Update the catalogue status to `Skeleton — needs parent review`.
9. Stop. Do not generate any section text in the same invocation.

## Later runs

- **Review skeleton:** revise outline/source notes, but do not draft story prose.
- **Write one section:** produce exactly one file in `sections/`, check its claims, then update progress.
- **Edit one section:** preserve meaning and citations; update source notes if factual changes are required.
- **Fact-check:** inspect the claim and its sources, correct or flag it, and do not automatically write new sections.

## Progress statuses

Use these values consistently:
- `Planned` — in the outline only.
- `Draft — parent review` — a section file exists but has not been approved by the parent.
- `Reviewed` — parent has approved the section.
- `Needs source review` — an authenticity or attribution question remains unresolved.
- `Revised` — changed after review.

Do not infer approval from the fact that a file exists.

## Outline template

Each section entry should contain:
- Section number and working title
- One-sentence event summary
- Primary source reference(s)
- Evidence label
- Intended value/moral
- Estimated read-aloud time
- Age adaptation note if needed
- Illustration direction (no prophets or Allah depicted)

The outline should also include:
- Book promise and intended age range
- Source limitations and chronology
- Values arc
- Repetition/pacing plan
- Material to exclude
- Parent-review questions

## Source register template

For every material claim, record:
| ID | Claim/event | Evidence label | Primary reference | Scholarly context | URL | Accessed | Used in story? |
|---|---|---|---|---|---|---|---|

Use the evidence labels in `guidelines/AUTHENTICITY.md`. If exact references or access dates cannot be verified, say so.

## Section template

See `guidelines/STORYTELLING.md`. Every section must be its own Markdown file and cite the sources it uses. The section's moral must follow from the event and may not be falsely attributed to scripture.

## Catalogue maintenance

After the first skeleton is saved, update the corresponding row in `catalogue/BOOKS.md` with the actual folder link and status. After each section, update the progress file. Only update the catalogue's completion state based on files that really exist.

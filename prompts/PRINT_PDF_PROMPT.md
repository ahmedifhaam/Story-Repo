# Prompt — Create Print-Ready A6 Islamic Children's Story PDFs

Use this prompt in an AI session that can read the Story-Repo files and create PDF files. It converts an **already researched and parent-reviewed book** into a print-ready, black-and-white A6 booklet. It must not invent, rewrite, or expand the religious story to fill a page.

---

## ROLE

You are a children's book typesetter, print-layout designer, and accessibility-minded document producer. Prepare small, memorable, easy-to-print storybooks for a home laser printer.

First read:
- `README.md`
- `guidelines/AUTHENTICITY.md`
- `guidelines/STORYTELLING.md`
- `guidelines/VALUES.md`
- `prompts/WORKFLOW.md`
- The selected book's `README.md`, `outline.md`, `sources.md`, `progress.md`, and all section files to be included.

If the user has not named a book, ask which existing book to format. Do not choose a book by guessing.

## NON-NEGOTIABLE OUTPUT REQUIREMENTS

1. **Paper:** A6 portrait, exactly 105 × 148 mm (4.13 × 5.83 inches).
2. **Printing:** black and white for a standard monochrome laser printer. Use pure black ink on a white background. No colour, grey-filled backgrounds, gradients, photographs, colour-dependent meaning, or large solid-black areas.
3. **Illustrations:** small, memorable, simple black line art with strong outlines and open white space. Prefer friendly, uncluttered, high-contrast shapes that remain clear when printed small.
4. **Prophets and Allah:** never depict any prophet, including as a silhouette, shadow, reflection, or symbolic human figure. Never depict Allah. Use landscapes, stars, trees, buildings, paths, boats, wells, tents, objects, plants, animals when appropriate, geometric motifs, and other setting-only scenes.
5. **Faithfulness:** use only the supplied approved story sections. Do not add religious claims, dialogue, events, or hadith. Do not remove a meaningful caveat or change a moral. If a source issue is noticed, stop and flag it instead of silently changing the story.
6. **Readable type:** use a clear, highly legible font. Body text should normally be around 11–12 pt on A6; do not go below 10 pt merely to force content onto a page. Use clear headings and generous line spacing.
7. **Printer-safe margins:** target at least 8 mm on every edge; use 10 mm where practical. Keep all text, page numbers, and essential illustration details inside the safe area. Do not use bleed unless specifically requested and supported by the print method.
8. **One-sided default:** design for ordinary single-sided printing unless the user explicitly requests duplex. Do not assume the printer can print borderless.
9. **Deliverable:** create a real PDF file and provide its verified download link. Also preserve or provide the editable source used to create the PDF (for example, a script or source document) when the environment supports it.

## ART DIRECTION

Create a warm, timeless picture-book feeling using only monochrome line art.

- Use a consistent illustration style throughout the book: simple contours, rounded shapes, a small number of clear objects, no unnecessary texture, no cross-hatching that becomes muddy, and no tiny detail.
- Prefer one small illustration per section or a few selected spreads rather than decorating every paragraph.
- Each illustration should help the child remember the setting or main idea, not dramatise suffering or invent historical specifics.
- Make illustrations small enough to leave room for text. As a guide, use one small illustration taking about 20–30% of a page, or a larger setting illustration on a page with very little text.
- Use open, white backgrounds. Avoid black blocks, dense patterns, delicate grey lines, and hairline strokes.
- Do not use generated images of prophets or historical people whose depiction would imply unsupported details. When in doubt, illustrate an object or setting instead.
- A caption may be used only if it helps the child and does not introduce unsupported historical claims.
- If an illustration cannot be produced safely or faithfully, use a simple decorative motif or omit it.

## PAGE DESIGN

- Format: A6 portrait, 105 × 148 mm.
- Safe margins: at least 8 mm, ideally 10 mm.
- Use a calm, consistent layout with a clear title, section heading, body text, and occasional illustration.
- Keep paragraphs short for read-aloud use. Avoid splitting a sentence across pages.
- Avoid placing a moral, vocabulary definition, or heading alone at the bottom of a page.
- Keep the moral visually distinct but do not put it inside a dark filled box. Use a thin black rule, simple outline, or whitespace instead.
- Include a discreet page number on interior pages if helpful. No page number is needed on the cover.
- Use black-only rules and borders, with restrained decoration.
- Avoid excessive headers and footers that steal precious A6 space.
- Do not squeeze the entire section onto one page if readability suffers. Allow a section to continue over multiple pages.
- Do not shrink text to preserve an arbitrary page count.

## BOOK STRUCTURE

Unless the parent requests another format, use this order:

1. **Cover:** book title, optional short subtitle, one small monochrome setting/object illustration, and “A read-aloud story for ages 3–6”.
2. **Inside title page (optional):** title and a brief family/library note. Do not invent a dedication or author's name.
3. **Story sections:** retain the approved section titles and exact approved story text. Include the section's moral and optional discussion/activity elements if present in the source.
4. **A small closing page (optional):** a brief, non-doctrinal goodbye or reflection only if already supplied/approved; do not invent new religious claims.
5. **Parent source notes:** by default, put the source references in a separate parent-facing final page or a separate companion file so the child's reading flow remains gentle. Do not omit source references from the project files. If the parent wants a child-only PDF, ask whether to include source notes separately.

Do not add a table of contents for a very short book unless it improves navigation.

## CONTENT HANDLING

- Preserve wording, punctuation, Islamic honorifics, vocabulary explanations, morals, and citations from the approved section files.
- Do not rewrite sections for layout without permission. If a small typographic correction is necessary, record it and keep the meaning unchanged.
- Do not combine sections in a way that removes their individual morals.
- Do not invent an author, publisher, ISBN, copyright notice, publication date, or logo.
- Keep parent-facing notes distinct from the child-facing story.
- Do not reproduce large blocks of external translations beyond what the source files lawfully contain. The PDF should use the project's own approved text and brief references.

## TECHNICAL PDF CHECKS

Before delivering the PDF, verify as much as the environment allows:

- PDF page size is A6 portrait (105 × 148 mm) on every page.
- Text is selectable/searchable when possible.
- Fonts are embedded or otherwise reliably supported.
- All pages are black and white; no colour objects or unintended grey backgrounds.
- No text, page numbers, or essential art are clipped or outside safe margins.
- Body text is legible at actual print size.
- No blank pages, broken glyphs, missing symbols, or corrupted Arabic/Unicode characters.
- Section titles and their opening text stay together where practical.
- No section or paragraph has been accidentally duplicated or omitted.
- Illustrations follow the no-prophets/no-Allah rule and do not add unsupported narrative details.
- The PDF opens successfully. If available, render pages to images and inspect every page at actual size.
- Report any checks that could not be performed; never claim to have verified a property you did not check.

If possible, include a contact sheet or low-resolution preview for quick review, but do not substitute a preview image for the PDF.

## WORKFLOW

1. Inspect the repository and identify the selected book.
2. Check `progress.md`. Prefer sections marked `Reviewed`. If only draft sections exist, tell the parent and ask whether to format them as drafts or wait for approval.
3. Read all sections to be included and confirm their source references are present.
4. Create a short layout plan: approximate page count, illustration locations, cover concept, and whether source notes will be included.
5. If the source text is incomplete, has unresolved source issues, or contains unreviewed sections, pause and ask the parent rather than making assumptions.
6. Produce the PDF with a reliable PDF-generation method available in the environment. If writing code, use a proper PDF layout library with explicit A6 page dimensions and print-safe margins.
7. Inspect the result using the technical checks above.
8. Save the PDF to the requested output location. If repository policy or user intent indicates the PDF should be committed, place it under `books/<category>/<book-id>/print/` and preserve the editable source. Otherwise provide the file to the user without changing the repository.
9. Report the exact output path, page count, page size, font-size range, illustration approach, included source notes, and any unverified checks.

## USER REQUEST TEMPLATE

When invoking this prompt, the parent may say:

> Create a print-ready A6 black-and-white PDF for `<book-id>`. Include only sections marked Reviewed. Use small, memorable, high-contrast line illustrations, never depict prophets or Allah, and include parent-facing source notes at the end or as a separate companion file. Preserve the approved story text and check every page before delivering.

## FINAL RESPONSE

Give:
- A verified link to the PDF.
- The editable source link if created.
- Page count and confirmation of A6 dimensions.
- A short note about print settings (A6 paper; actual size/100%, not “fit to page”, unless the printer requires otherwise).
- Any limitations or checks not completed.

Never claim a file exists unless the output file was actually created and its path verified.

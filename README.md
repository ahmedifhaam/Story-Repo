# Story-Repo — Islamic Stories for Growing Hearts

A carefully researched, growing library of read-aloud stories for children aged **3–6**. The goal is to nurture love of Allah, good character, curiosity, and a warm connection to Islamic history through short, engaging stories.

## Our principles

- **Authenticity before drama.** Start with the Qur'an, then use sound, well-attributed Sunni sources. Never invent religious claims, hadith, events, quotations, or miracles.
- **Age-aware, not one-size-fits-all.** Write for ages 3–6, with simple core language and optional small challenges for older listeners.
- **Read aloud.** Aim for 4–5 minutes per section, with natural rhythm, repetition, sensory details, and gentle curiosity.
- **Teach through the story.** End every section with one short, warm moral tied to the sourced events.
- **Respectful imagery.** Never depict any prophet. Prefer landscapes, buildings, objects, maps, plants, and other setting-focused illustrations. Do not depict Allah.
- **Clear English.** Use familiar words. Explain an occasional useful unfamiliar word immediately in brackets.
- **Transparent uncertainty.** Mark disputed or weak reports and normally exclude them from the child's narrative.

## Start here

1. Read [the source and authenticity policy](guidelines/AUTHENTICITY.md).
2. Read [the storytelling guide](guidelines/STORYTELLING.md).
3. Review the [book catalogue](catalogue/BOOKS.md).
4. Use [the master prompt](prompts/MASTER_PROMPT.md) when working with an AI assistant that can research the web and edit repository files.
5. Use [the workflow](prompts/WORKFLOW.md) to create or continue a book without generating it all at once.
6. Use the [A6 print PDF prompt](prompts/PRINT_PDF_PROMPT.md) to format reviewed stories as monochrome, laser-printer-friendly booklets.

## Repository layout

```text
Story-Repo/
├── README.md
├── guidelines/
│   ├── AUTHENTICITY.md
│   ├── STORYTELLING.md
│   └── VALUES.md
├── prompts/
│   ├── MASTER_PROMPT.md
│   ├── PRINT_PDF_PROMPT.md
│   └── WORKFLOW.md
├── catalogue/
│   └── BOOKS.md
└── books/
    ├── prophets/
    ├── prophet-muhammad/
    ├── companions/
    └── everyday-islam/
```

Git does not track empty directories, so each book directory will gain its own files when its first outline is created.

## How book creation works

**First invocation for a book:** research the topic, record sources, propose a section-by-section outline, and save a reviewable skeleton. Do not write the complete book.

**Later invocations:** review and improve the outline or write exactly one requested section. Save it as a separate file, include its sources and moral, and update the progress tracker. Never generate multiple story sections in a single run unless the parent explicitly asks for that.

## How printable PDFs work

Use `prompts/PRINT_PDF_PROMPT.md` after the story sections have been reviewed. It specifies **A6 portrait (105 × 148 mm)**, pure black-and-white line art for a monochrome laser printer, printer-safe margins, readable type, and the rule that prophets and Allah must never be depicted. It instructs the PDF creator to preserve approved text, check every page, and provide a verified PDF file.

## Suggested first book

Start with **Prophet Yusuf (Joseph): A Story of Patience and Forgiveness**, because the Qur'an gives a substantial, coherent account in Surah Yusuf. Research the Qur'anic account carefully and design the story for ages 3–6 without adding unsupported dialogue or details.

## Age range

- **Ages 3–4:** short sentences, concrete actions, repetition, gentle emotions, one clear moral, and a caregiver reading aloud.
- **Ages 5–6:** retain clear language but allow richer connections, slightly more detail, and an optional question for discussion.
- Every section should work for the younger end; optional “For curious listeners” notes can extend the conversation for older children without making the main story harder.

## Quality checklist

Before publishing any section, confirm:
- [ ] Every factual religious claim is traceable to a recorded source.
- [ ] Qur'an references include surah and ayah numbers.
- [ ] Hadith references include collection and identifier where reliably available; grading and attribution are checked.
- [ ] No invented quotes, dialogue, thoughts, scenes, or religious teachings are presented as fact.
- [ ] The section is age-appropriate and roughly 4–5 minutes when read aloud.
- [ ] A single clear moral follows naturally from the story.
- [ ] No prophet is depicted in an illustration.
- [ ] New vocabulary is explained in brackets at first use.
- [ ] The book's outline and progress tracker match what has actually been completed.

## Scope note

This is a family storytelling project, not a substitute for scholarly study or religious rulings. If a source's authenticity or meaning cannot be resolved confidently, flag it for parent review instead of guessing.

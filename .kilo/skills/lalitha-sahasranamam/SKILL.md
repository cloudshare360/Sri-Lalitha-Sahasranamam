---
name: lalitha-sahasranamam
description: Locate, quote, verify, compare, or export stanzas from this repository’s Lalitha Sahasranamam PDF and searchable Markdown transcription.
---

# Source edition

- Canonical file: `docs/02-Lalitha_Sahasra_Namamulu_English.pdf`; searchable transcription: `docs/01-Lalitha_Sahasra_Namamulu_English.md`. See `docs/README.md` for the reading order and references.
- Printed title: `SHRI LALITHA SAHASRANAMAM IN ENGLISH`; embedded title: `SREE LALITHA SAHASRANAMA STOTRAM`. Sanskrit in nonstandard Latin romanization, not English translation or IAST. The preamble states `anushtup chandaha`; this is not an independent metrical verification.
- 18 US Letter pages, extractable text, unencrypted; SHA-256 `dcd51f7cf06f37ea35ca0f7f527b7c8df2d14d666ea24c766c309e229fbadfb5`.
- Embedded file metadata: Author `Venkata`, Company `Home`, Creator `Acrobat PDFMaker 9.1 for Word`, Producer `3.0.31 (5.1.18)`; created 2011-09-26 14:47:40 UTC, modified 2026-03-07 11:55:33 UTC. These fields do not establish hymn authorship or publication dates. The domains on pp. 1 and 8 are printed footer text, not verified credits.
- P. 1: illustrated cover. P. 2: unnumbered ritual preamble ending `jape viniyogah`, then `DHYANAM` with five visually separated blocks. Pp. 3–18: 183 two-line numbered stanzas. The second line of stanza 183 is a concluding statement; the separate unnumbered `Sree Lalitha Sahasranama Stotram Samaptam` follows. No separate phalaśruti follows in this file.

| PDF page | Printed stanzas |
| --- | --- |
| 3 | 1–11 |
| 4 | 12–23 |
| 5 | 24–35 |
| 6 | 36–47 |
| 7 | 48–59 |
| 8 | 60–71 |
| 9 | 72–83 |
| 10 | 84–95 |
| 11 | 96–107 |
| 12 | 108–119 |
| 13 | 120–131 |
| 14 | 132–143 |
| 15 | 144–155 |
| 16 | 156–167 |
| 17 | 168–179 |
| 18 | 180–183 |

# Workflows

- **Lookup and quotation:** Search Markdown first, allowing for spelling variants in queries. Quote the source spelling and cite PDF page and stanza, e.g. `p. 9, stanza 76`. Check the rendered PDF if extraction and appearance disagree.
- **Transcription:** Preserve case, spelling, punctuation, and the two verse lines. Keep preamble, dhyanam, pagination, and completion line outside the numbered records. Parse trailing numbers, not blank lines or a mandatory dash: stanza 76 has no dash, and 36/37, 103/104, and 140/141 lack a blank separator in the PDF. Remove page footers from verse parsing. Validate 1–183 in order, with two lines each (366 total), and check each PDF page range against the table.
- **Comparison and interpretation:** Label standardized Sanskrit, IAST, pronunciation, translations, and commentary as derived material. Identify the edition used for comparisons and never silently substitute its wording in the transcription.
- **Structured export:** Use one record per numbered stanza with `stanza_number`, `pdf_page`, and `lines` (two source lines). If the trailing printed label is separated from the text, retain its original formatting separately for round-trip fidelity. Do not split names on spaces or hyphens or use stanza numbers as name IDs; use a separately sourced name index if requested.

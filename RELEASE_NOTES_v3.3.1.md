# Law Journal Workbench v3.3.1 — Editor Preview

## Choose one download

- **Windows 10/11:** `LawJournalWorkbench-v3.3.1-Windows.zip`
- **Apple Silicon Mac:** `LawJournalWorkbench-v3.3.1-macOS-Apple-Silicon.zip`
- **Intel Mac or no-install evaluation:** use the web edition.

Each ZIP contains a plain-language `START HERE` guide. The macOS build is not
signed with an Apple Developer certificate; its guide explains the expected
first-launch security prompt without requiring Terminal.

> GitHub also displays automatically generated **Source code** archives below.
> Editors do not need those files. Download the named application package for
> the computer you are using.

## New in v3.3.1

- **PDF typeface parity.** Text-based PDFs with embedded font information now
  receive citation-component checks for italics, bold, underline, and small
  caps through the same review rules used for DOCX drafts.
- **Honest uncertainty.** Scanned, image-only, or ambiguously encoded PDFs keep
  typography unasserted instead of creating false formatting errors.
- **More reliable PDF footnotes.** Superscript note numbers, wrapped volume
  numbers, and Word-style split small-cap glyphs retain their reading order.
- **Secondary-source extraction polish.** Uppercase journal abbreviations and
  institutional government reports are recognized more reliably without being
  mistaken for case short forms.

## Verification

- Automated suite: 272 tests and 13 subtests passed locally and in GitHub
  Actions.
- Four real DOCX/PDF pairs produced identical citation counts and typeface
  judgments: 39, 40, 40, and 141 citations.
- The packaged Windows application launched successfully.
- Desktop and 390-pixel mobile web layouts were visually checked.
- Windows ZIP SHA-256:
  `B2E4EA5716868A027FBB807C40CC21E4234ACCFB34530A3374896746A3B06B7F`
- macOS ZIP SHA-256:
  `027BED7DE41BE6D25FB5F1AE3AB7718BBF68FA5E85B5F5AD68E255E706A93E8A`

## Web edition and feedback

The hosted web edition is available at
https://law-journal-workbench.onrender.com. The first visit may take about a
minute while the free instance wakes. Please send incorrect classifications,
difficult citations, and workflow feedback to anthony.woodside@ubalt.edu.

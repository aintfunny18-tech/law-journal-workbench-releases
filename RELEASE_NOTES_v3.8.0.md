# Law Journal Workbench v3.8.0 — Editor Preview

## Choose one download

- **Windows 10/11:** `LawJournalWorkbench-v3.8.0-Windows.zip`
- **Apple Silicon Mac:** `LawJournalWorkbench-v3.8.0-macOS-Apple-Silicon.zip`
- **Intel Mac or no-install evaluation:** use the web edition.

Each ZIP contains a plain-language `START HERE` guide. The macOS build is not
signed with an Apple Developer certificate; its guide explains the expected
first-launch security prompt without requiring Terminal.

> GitHub also displays automatically generated **Source code** archives below.
> Editors do not need those files. Download the named application package for
> the computer you are using.

## New in v3.8.0

- **Bluebundle Assistant.** Review one or several printed footnotes through
  manuscript context, labeled Bluesheets, pulled sources, assembled-bundle QA,
  and recorded editor decisions.
- **Practitioner / Bluepages Review.** Use an explicit practitioner-document
  path with B1-B23 coverage labeled automated, provisional, manual, or
  citation-adjacent.
- **Conservative evidence checks.** The assistant inspects real PDF bookmarks,
  live highlights and underlines, source/page fingerprints, image-only pages,
  repeated material, and source order without rewriting files or declaring
  substantive legal support.
- **Portable progress.** Desktop review state persists locally. A versioned
  `.ljw-review.json` file carries hashes, findings, and decisions without
  manuscript text, source text, or embedded private files.
- **Desktop/web parity.** Both applications use the same canonical engine and
  profile. The web edition supports multi-footnote numbered artifacts, editor
  confirmations, DOCX/CSV exports, explicit deletion, and enforced 30-minute
  expiry.

## Verification

- Automated suite: 465 tests and 121 subtests passed locally and in GitHub
  Actions.
- Cases/periodicals qualification: 80/80; public-law qualification: 100/100.
- Six-document citation corpus remained exact at 64/34/61/40/69/44.
- All 34 private Carroll 090-123 reviews completed without a crash. Thirty-two
  correctly remained at editor confirmation; footnotes 116 and 117 remained
  not ready for a genuine missing-comma defect.
- The packaged Windows application launched responsively as v3.8.0; the macOS
  package built successfully in GitHub Actions.
- Windows ZIP SHA-256:
  `3EE0B3DB02A6462464C81C0492B3CC6E2404FE978806116927E6515143D33A76`
- macOS ZIP SHA-256:
  `808E4E2021ABBC05FB84BE5C660188B12489AB971B32DD84C0C5F00482D08072`

## Scope and feedback

`assistant_checks_complete` means only that configured checks and recorded
human confirmations are complete. It is not proof that a citation or
proposition is legally correct, and the Workbench makes no universal
Bluebook-compliance claim.

The hosted web edition is available at
https://law-journal-workbench.onrender.com. Please send incorrect
classifications, difficult citations, and workflow feedback to
anthony.woodside@ubalt.edu.

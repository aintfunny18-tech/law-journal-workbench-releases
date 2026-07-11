# Law Journal Workbench v3.3.0 — Editor Preview

Law Journal Workbench helps law-journal editors organize the mechanical first
pass of citation review while preserving editorial judgment.

## Choose one download

- **Windows 10/11:** `LawJournalWorkbench-v3.3.0-Windows.zip`
- **Apple Silicon Mac (M1, M2, M3, M4, or later):** the macOS package is
  currently the v3.2.0 build, available from the
  [v3.2.0 release](https://github.com/aintfunny18-tech/law-journal-workbench-releases/releases/tag/v3.2.0).
  A v3.3.0 macOS build will follow.
- **Intel Mac:** use the web edition for this release.

Each ZIP contains a `START_HERE` file with platform-specific instructions.

> GitHub also displays automatically generated **Source code** archives below.
> Editors do not need those files. Download the named application package above.

## New in v3.3.0

- **Source verification beyond cases.** Project libraries and Full Source
  Check now accept law-review articles, books and partial book scans, webpage
  printouts, newspapers, and government reports. Pincites are verified against
  each source's own printed page numbers; sources without reliable pagination
  are checked source-wide and clearly labeled as such — a source-wide match is
  never presented as proof of a cited page.
- **Check One Citation.** Paste a single citation on the home screen (desktop
  or web), mark its italics, bold, underline, and small caps, and get an
  immediate review. Malformed citations receive conservative recovery and safe
  mechanical suggestions instead of a "no citation detected" dead end.
- **Two new editor deliverables:** a numbered footnote/endnote correction
  sheet and a citation-change ledger (original, corrected form, resolved full
  citation, explanation, and Bluebook rules).
- **Journal-workflow source-pull checklist** ordered as pull → substantive,
  quotation, and pincite review → Bluebook form, with assignment and status
  columns.
- Hardened scholarly-periodical and string-citation detection, saved-HTML
  source ingestion, and an adversarial-input hardening pass across the
  single-citation checker (see the project CHANGELOG for details).

## Highlights carried forward

- Quick Citation Audit for project-free citation-form review.
- Local project dashboards, reusable source libraries, and the Full Source
  Check readiness preview.
- Resizable citation-results cockpit with findings, source evidence, and
  editor decisions.
- Reporter-specific page matching for parallel reporters; footnote and
  endnote extraction; light and dark themes.

## Privacy and limitations

Desktop projects, manuscripts, and source libraries remain on the editor's
computer. Suggestions are read-only and do not silently rewrite uploaded
documents. Law Journal Workbench assists with citation review; it does not
replace Bluebook judgment, source review, or substantive legal analysis.

## Verification

- Automated suite: 261 tests and 13 subtests passed; adversarial
  single-citation stress harness (66 malformed inputs) ran crash-free.
- Windows ZIP SHA-256:
  `4DFAF6AA0179AE0F7B780AD90A9AF9B97BE0EA14A9AE048B3FC822511F9374BB`

## Web edition and feedback

The hosted web edition is available at
https://law-journal-workbench.onrender.com (the first visit may take about a
minute while the free instance wakes). Please send incorrect classifications,
difficult citations, and workflow feedback to anthony.woodside@ubalt.edu.

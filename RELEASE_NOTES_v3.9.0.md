# Law Journal Workbench v3.9.0 — Streamlined Bluesheet and Bluebundle checks

## What changed

- **Bluesheet Check** accepts one or more Bluesheet DOCX/PDF files and checks
  Old Cite, New Cite, and Correct Full Cite without requiring an assignment,
  printed-footnote entry, or separate source uploads.
- **Bluebundle Check** accepts one or more assembled PDFs, treats the first
  page as the Bluesheet, and inspects the pages after it as the attached source
  set. A one-page bundle remains reviewable and clearly reports that no source
  pages were detected.
- An optional manuscript adds exact Old Cite comparison and proposition/
  quotation review. Without it, the standalone checks remain useful and do not
  fail solely because the optional input was omitted.
- New Full Cite is parsed as a distinct corrected long-form field. DOCX run
  formatting is preserved for small caps, italics, and underlining; PDF
  typeface conclusions are labeled reduced-confidence.
- Internal cross-references and constitutional citations receive tailored
  manual prompts. A multi-page standalone Bluesheet PDF suggests the
  Bluebundle workflow so attached source pages are not overlooked.
- The existing assignment queue, source reuse, editor decisions, and portable
  review state remain available under **Advanced assignment tools**.
- Practitioner / Bluepages Review remains separate and explicitly uses its
  practitioner-document convention with B1-B23 coverage labels.
- Desktop quick-review results now show the same citation-field summary and
  Fix before finishing / Confirm manually / Checks passed groups as the web
  workspace.

## Verification

- Local suite: **471 tests passed and 121 subtests passed**.
- All **34 Carroll Bluesheets** and **34 Carroll Bluebundles** parsed without
  crashes; all five Bluepages example PDFs were validated as bundles.
- Real-data checks found no false missing-Nota-Bene findings and mapped DOCX
  small-caps formatting from actual runs.
- Web batch parity produced matching canonical engine results for identical
  artifacts. The rebuilt Windows package launched successfully.

## Downloads

- Windows 10/11: `LawJournalWorkbench-v3.9.0-Windows.zip`
- Apple Silicon Mac: `LawJournalWorkbench-v3.9.0-macOS-Apple-Silicon.zip`
- Web edition: https://law-journal-workbench.onrender.com

SHA-256 checksums:

- Windows: `2427CB40EFFA635300382BBD939E2B9BD0B4F70B0251113F7CC50385016680D3`
- macOS: `9E26158D197DC3836EA52FDED7A1C2DC35AD5CE4FB87CE5FD4282C89AB328DE5`

## Scope

The Workbench double-checks production work; it does not rewrite documents,
assemble bundles, submit sources, or declare substantive legal support. A
manual confirmation remains required wherever the configured checks cannot
establish the result safely.

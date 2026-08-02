# Law Journal Workbench v3.9.1 — Bluebundle reliability update

## What changed

- Multi-page Bluesheet continuations are no longer counted as attached source
  pages in Bluebundle results.
- When New Cite is a short form such as `supra`, Correct Full Cite now supplies
  the identity and source family used for attached-source requirements.
- Wrapped web URLs and the lowercase title word `from` are handled correctly
  in text-layer PDF Bluesheets.
- Likely missing-rule prompts recognize rule numbers with or without the word
  `Rule`, suppress redundant parent rules, and appear under Confirm manually.
- Desktop and web summaries now use the same multi-page Bluesheet parser.
- Quick-review downloads use clear Bluesheet Review or Bluebundle Review names;
  portable review state remains confined to Advanced assignment tools.

## Verification

- **477 tests and 121 subtests passed** locally and the GitHub test workflow
  passed on the release commit.
- Both qualification suites passed: 80/80 cases and periodicals and 100/100
  public-law samples.
- The six-document corpus regression passed with exact expected counts.
- All **34 Claude Carroll Bluesheets** and **34 Carroll Bluebundles** completed
  without crashes, blocking findings, false missing-Nota-Bene findings, or
  generic parse warnings.
- All five supplied Bluepages examples completed without crashes. The Internet
  example remains not ready only because its web citation lacks the configured
  permanent-archive treatment.
- The macOS package built successfully in GitHub Actions. The Windows package
  built successfully and contains the required pypdf runtime and UB profile;
  local Application Control prevented executing the newly generated EXE.

## Downloads

- Windows 10/11: `LawJournalWorkbench-v3.9.1-Windows.zip`
- Apple Silicon Mac: `LawJournalWorkbench-v3.9.1-macOS-Apple-Silicon.zip`
- Web edition: https://law-journal-workbench.onrender.com

SHA-256 checksums:

- Windows: `46E367CF43BC65A64CEED15EAEB09FB073260A1CCFB11BAF731EE547D251D96C`
- macOS: `1FA5F37AEDE6F24EA2B188FBFFF084308D5D15BA5119A5E0A0C911770CD95633`

## Scope

The Workbench double-checks production work. It does not rewrite documents,
assemble bundles, submit sources, or declare substantive legal support. A
manual confirmation remains required wherever the configured checks cannot
establish the result safely.

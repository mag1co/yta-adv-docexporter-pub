# Changelog

## v1.0.13

- Security: added safe url guard for XLSX hyperlinks (both single-cell and multi-run)
- Security: added safe url guard for DOCX table hyperlinks
- Refactoring: dry refactoring
- Fix: corrected table heading detection — use line index instead of `indexOf` to avoid wrong heading for duplicate table rows

## v1.0.12

- Security: sanitize URL schemes in hyperlinks during Office export (block javascript:, file://, etc.)
- DOCX: blockquote styling with grey left border

## v1.0.11

- Renamed app display title to Adv.DocExporter
- Updated logging to be more centralized and context-aware
- Normalized app to comply with updated Marketplace guidelines

## v1.0.1

- Security: added READ_ARTICLE permission check on global /export endpoint

## v1.0.0

- First stable release
- Published to JetBrains Marketplace (Stable channel)
- Project-level settings: file name prefix, date suffix, notification mode
- EULA, PRIVACY, GETTING_STARTED for Marketplace listing
- Publish and sync scripts for Marketplace, GitLab, public GitHub

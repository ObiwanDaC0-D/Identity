# Identity Atlas V12 — Source-level usability audit

## Reviewed
- Both standalone HTML pages exist and have cross-navigation.
- The Atlas has 28 frameworks and six learning pathways.
- The Research Studio contains 34 curated source records.
- Mobile navigation and safe-area padding are defined on both pages.
- Research Studio notes now fall back to in-memory storage if browser storage is blocked; the user sees a temporary-session warning.
- Progress language clarifies that persistence depends on browser storage.

## Live-browser acceptance checklist — pending
1. iPhone Safari: verify responsive layout, no horizontal overflow, visible controls and bottom navigation.
2. Search by theory, thinker and concept; clear filters and verify all entries return.
3. Open theory profiles and expand all scholarly sections.
4. Test correct and incorrect quiz responses.
5. Add, remove and compare frameworks.
6. Mark learning-path entries complete, reload, and verify persistence.
7. Filter Research Studio by source type and theory.
8. Save, export, clear and import research notes.
9. Block local storage and confirm temporary-note behavior and warning.
10. Copy citations and BibTeX; verify clipboard output.
11. Test keyboard focus and screen-reader labels.

This was a **code review and resilience patch**, not a completed live-browser interaction test. Deployment and iOS behavior remain to be verified.

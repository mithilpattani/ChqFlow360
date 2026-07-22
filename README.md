# ChqFlow360 Prototypes

Live product demo: https://mithilpattani.github.io/ChqFlow360/
Live test console: https://mithilpattani.github.io/ChqFlow360/test-console.html

`index.html` is the scripted Live Demo (5 pre-written cheques) — this is
the presentation-facing product demo, with a "+ New Cheque" button on
the Dashboard that opens the Test Console in a new tab, and a working
Standalone/Embedded mode switch in the top bar.

`test-console.html` is a genuinely functional tool, not scripted:
real file upload, real amount-in-words/figures hygiene check (actual
Indian Lakh/Crore word conversion), real post-dated/stale date checks,
real duplicate cheque-number detection (persisted via local storage),
and a real maker-checker workflow with a live Audit Log. OCR and the
signature-match score are simulated seed values you can edit — clearly
labeled in the tool. 12 built-in test cases on its Library tab.

Both link back to each other, so the whole thing browses as one
connected product rather than two separate files.

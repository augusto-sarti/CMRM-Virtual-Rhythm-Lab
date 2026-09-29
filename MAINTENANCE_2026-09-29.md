# Maintenance pass - 2026-09-29

Changes made following Riccardo's review:

- Markdown math in current `notebooks/` and `executed/` uses `$...$` and `$$...$$` delimiters rather than `\\(...\\)` and `\\[...\\]`.
- Accidental control-character corruption in a few LaTeX commands (`\\boxed`, `\\text`, `\\tau`, `\\to`) was repaired.
- HTML previews for Labs 03 and 06 were regenerated from the corrected executed notebooks.
- The Polymetric Visualizer is linked at the public GitHub Pages address and a self-contained offline copy is included under `interactive/polymetric-visualizer/index.html`.
- Legacy notebooks under `legacy_notes/` were intentionally left unchanged as archival source material.

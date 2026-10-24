---
name: xxd-panel-115
description: "XXD Panel 115｜Pastel Stamp Collage Journal: rebuilds the core subject and mood of a photo as a small, seal-like pastel doodle on vintage paper — chalk or crayon lines that vary in weight, with dry grain, broken powdery strokes, slight wobble and open edges, a few short strokes, cross-hatching or simple grids for structure, a little paper-scrap collage, a few tiny stars, flowers, ripples or symbols as echoes, a kraft, recycled or pale handmade paper ground that stays clearly distinct from the subject, large deliberate whitespace, two to four soft pastels from the photo brightened with white or cream lines, and a few thin, airy typewriter-style words. Outputs PNG top-bottom or left-right comparisons, design-only images, or phone/tablet/desktop/watch wallpapers, from one photo or a folder. Use when the user invokes xxd-panel-115 or asks for pastel chalk doodle, crayon stamp-like collage or vintage-paper sketch art from a photo."
---

# XXD Panel 115

Create finished PNG artwork from the current user-supplied photograph or image directory. Read `references/original-prompt/zh-CN.md` completely immediately before every generation. That Chinese source brief is the sole creative and aesthetic authority; never summarise, translate, blend, or replace it with this file, a README, a sample, or another Panel.

Read `references/soldier-runtime.md` completely immediately before building every generation request. It is the sole family runtime contract for parameters, preference reuse, directory batches, preflight, prompt assembly, bitmap execution, output isolation, and acceptance. This Skill must not write a second art direction or a second runtime.

## Panel-specific overlay

Use `scripts/compose_panel.py` only for exact raster sizing, pixel-preserving composition, or read-only audits; it must never invent or redraw the design. For linked wallpapers, create one anchor from the original source, then independently recompose each remaining device from the original source plus that anchor.

These overlay rules add to `references/soldier-runtime.md`. They never replace the source brief or the family runtime contract.

Write every selected final PNG directly inside one fresh task directory under `~/Desktop/xxd/xxd-panel-115/` (or the explicit `--out` root). Use collision-safe filenames; do not create source, mode, or size subdirectories and do not generate an automatic contact sheet.

## References

- `references/soldier-runtime.md` — family runtime contract used at generation time
- `references/original-prompt/zh-CN.md` — canonical source brief used at runtime
- `references/original-prompt/README.md` — translation index and authority note
- `references/runtime-preferences.md` — safe delivery-preference reuse
- `references/sample-workflow.md` — sample-artwork maintenance only; never a runtime prerequisite
- `references/xxd-panel-115-prompt.zh-CN.md` and `.en.md` — delivery adapter notes matching the family runtime blocks

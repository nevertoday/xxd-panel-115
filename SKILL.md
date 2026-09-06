---
name: xxd-panel-115
description: "Create XXD Panel 115 raster posters by preserving the source photograph above and reinterpreting its core memory below as a pastel-crayon doodle and material collage stamp on textured vintage paper. Supports isolated images, directory batches, strict 50:50 comparisons, design-only work, and wallpaper packs."
---

# XXD Panel 115

Create finished PNG artwork from the user's photograph or image directory. Read `references/original-prompt/zh-CN.md` completely immediately before every generation. That Chinese source brief is the sole creative and aesthetic authority; never summarise, translate, blend, or replace it with this file, a README, a sample, or another Panel.

## Delivery contract

- One source photograph produces isolated outputs; never combine sources or reuse another source's subject, wording, or result.
- The canonical presentation is a 3:4 portrait canvas: reality above and the pastel collage transformation below, exactly 50:50. Support `top-bottom`, `left-right`, `design-only`, and `wallpaper-pack`.
- Comparison modes have exactly two equal regions, no header, footer, inset, grid, or third band. `left-right` keeps reality left; it must not silently become an upper/lower layout.
- A directory is explicit batch intent: inventory supported raster files in stable order, report the count, resolve shared settings once, generate each independently, and account for every success and failure.
- Resolve modes, sizes, text mode, locale, wallpaper relationship, device sizes, and output root before generation. Do not infer a silent ratio or locale.

## Prompt authority

For each output, concatenate the complete verbatim Chinese source brief, a short delivery preamble, exactly one mode contract, exactly one text contract, and only explicit non-style requirements. Runtime additions may change delivery variables only; never add a fixed palette, title, slogan, or aesthetic theory.

Text modes are `prompt`, `exact`, and `none`. Resolve the target locale explicitly. Exact text is passed verbatim; text-free output contains no letters, numbers, logos, labels, or pseudo-text. Prefer one complete-canvas generation per distinct output; never feed an intermediate stylisation, sample, or another Panel's result through a second pass.

## Output and acceptance

Write final PNGs directly inside one fresh task directory under `~/Desktop/xxd/xxd-panel-115/` or the explicit output root. Do not create source, mode, or size subdirectories or automatic contact sheets. Inspect every result at full and thumbnail size. Accept only when source visibility, ratio, split direction, exact 50:50 midpoint, lower-panel correspondence, typography mode, and absence of watermarks, SVG substitutes, UI, third bands, or second-pass artefacts are correct.

Use `scripts/compose_panel.py` only for exact raster sizing, pixel-preserving composition, or read-only audits; it must never invent or redraw the design. For linked wallpapers, create one anchor from the original source, then independently recompose each remaining device from the original source plus that anchor.

## References

- `references/original-prompt/zh-CN.md` — canonical verbatim source brief
- `references/original-prompt/README.md` — translation index and authority note
- `references/runtime-preferences.md` — safe delivery-preference reuse
- `references/xxd-panel-115-prompt.zh-CN.md` and `.en.md` — delivery adapter notes

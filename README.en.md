<div align="center">

# XXD Panel 115｜Pastel Stamp Collage Journal

Rebuild a photograph's core memory as a pastel hand-drawn collage stamp on vintage paper

<a href="README.md">简体中文</a> · <strong>English</strong> · <a href="README.ja.md">日本語</a> · <a href="README.ko.md">한국어</a> · <a href="README.ar.md">العربية</a>

</div>

## 16:9 Left–Right Samples

Four independent sources on complete 16:9 canvases: reality left, this Panel's design right, exact 50:50. English copy is generated from each photograph.

<table>
  <tr>
    <td width="50%"><img src="./assets/examples/sample-05.png" alt="XXD Panel 115 Sample 5"></td>
    <td width="50%"><img src="./assets/examples/sample-06.png" alt="XXD Panel 115 Sample 6"></td>
  </tr>
  <tr>
    <td width="50%"><img src="./assets/examples/sample-07.png" alt="XXD Panel 115 Sample 7"></td>
    <td width="50%"><img src="./assets/examples/sample-08.png" alt="XXD Panel 115 Sample 8"></td>
  </tr>
</table>

## 3:4 Top–Bottom Samples

Four further independent sources, different from the 16:9 set, regenerated as complete 3:4 top–bottom canvases. The original photograph remains above; the lower design follows this Panel's original brief.

<table>
  <tr>
    <td width="50%"><img src="./assets/examples/sample-09.png" alt="XXD Panel 115 additional top-bottom sample 1"></td>
    <td width="50%"><img src="./assets/examples/sample-10.png" alt="XXD Panel 115 additional top-bottom sample 2"></td>
  </tr>
  <tr>
    <td width="50%"><img src="./assets/examples/sample-11.png" alt="XXD Panel 115 additional top-bottom sample 3"></td>
    <td width="50%"><img src="./assets/examples/sample-12.png" alt="XXD Panel 115 additional top-bottom sample 4"></td>
  </tr>
</table>

## Sample gallery

**16:9 landscape left–right samples (source left, design right, strict 50:50)**

| sample-05 | sample-06 |
|---|---|
| ![XXD Panel 115 landscape sample 1](assets/examples/sample-05.png) | ![XXD Panel 115 landscape sample 2](assets/examples/sample-06.png) |
| ![XXD Panel 115 landscape sample 3](assets/examples/sample-07.png) | ![XXD Panel 115 landscape sample 4](assets/examples/sample-08.png) |

**3:4 portrait top–bottom samples (source above, design below, strict 50:50)**

| sample-09 | sample-10 |
|---|---|
| ![XXD Panel 115 portrait sample 1](assets/examples/sample-09.png) | ![XXD Panel 115 portrait sample 2](assets/examples/sample-10.png) |
| ![XXD Panel 115 portrait sample 3](assets/examples/sample-11.png) | ![XXD Panel 115 portrait sample 4](assets/examples/sample-12.png) |

The eight works use different original reference images. Panel 115 generated each one independently in a single pass from its own canonical prompt; no work from another numbered Panel or intermediate result was reused. AI-generation and provenance metadata have been removed from every sample.

## Where this Panel fits — and what it solves

When a photograph is redesigned for a poster, cover, social post, or exhibition image, it is easy to trace every object, fill the page, or apply a sugary children's-collage template until the original relationship and breathing room disappear.

**Panel 115** treats every photograph as its own 3:4 portrait poster. The upper half preserves photographic reality; the lower half interprets the most memorable theme, relationship, structural direction, emotion, and visual metaphor as a pastel hand-drawn material collage on textured vintage paper. A small stamp-like subject, deliberate whitespace, two to four lively source-derived colours, and sparse light type create a clever, airy restatement.

It addresses literal object-by-object copying, muddy separation, overfilled layouts, realistic rendering, smooth vectors, excessive decoration, childish templates, 3D styling, and generic commercial-poster polish.

## Usage tips

- **Start with one clear photo:** choose a source whose subject, action, and relationships are easy to recognize before choosing the delivery format.
- **Join the parameters in one sentence:** say “top-bottom / left-right / design-only + 16:9 / 3:4 / phone wallpaper”; you can also name desktop, tablet, or smartwatch sizes.
- **State what must stay:** identify the people, objects, actions, relationships, and copy to preserve, while leaving room for the style to design the layout.
- **Choose a text mode:** let the model write from the image, lock exact wording with `--text exact --copy`, or remove text completely with `--text none`.
- **Clarify reality and design regions:** for top-bottom or left-right, say which region keeps the photograph and which region is redesigned; for design-only and wallpapers, say that the whole canvas is redesigned.
- **Test one image before batching:** confirm mode, ratio, text, and language on one source, then reuse the settings for a folder; change one variable per iteration.

## Get started

```bash
git clone https://github.com/nevertoday/xxd-panel-115.git
mkdir -p ~/.codex/skills
ln -s "$(pwd)/xxd-panel-115" ~/.codex/skills/xxd-panel-115
```

Or install directly with `npx skills`:

```bash
npx skills add https://github.com/nevertoday/xxd-panel-115 --skill xxd-panel-115
```

Append `--global --agent codex --yes` for a user-level Codex installation. Restart the agent session, then invoke `$xxd-panel-115`.

## Original prompt · five languages

[简体中文](references/original-prompt/zh-CN.md) · [English](references/original-prompt/en.md) · [日本語](references/original-prompt/ja.md) · [한국어](references/original-prompt/ko.md) · [العربية](references/original-prompt/ar.md)

The Chinese file preserves the user's original prompt verbatim and is the sole runtime creative and aesthetic authority. The other four files are complete, faithful reading translations and never rewrite the generation prompt.

**Keywords:** strict 3:4 50:50 · vintage paper texture · pastel-crayon doodle · material collage · small stamp-like subject · 2–4 source-derived colours · deliberate whitespace · light typewriter typography

## Is Panel 115 right for you?

| What you need | What this style provides |
|---|---|
| A comparison poster rather than another filter? | Reality stays above, while the lower half is independently rebuilt as paper-and-pastel collage, exactly 50:50. |
| A recognisable subject without visual crowding? | Only essential contour, pose, direction, and relationships remain, composed as a small stamp in generous whitespace. |
| Friendly colour without cheap candy styling? | Two to four representative colours are drawn from the photograph and remixed into a clear, warm pastel group. |

## Capabilities and boundaries

Every source is generated independently. Never combine photographs or feed an intermediate, sample, or another Panel's result through a second transformation. The canonical output is a 3:4 portrait with a strict 50:50 top–bottom split; `left-right`, `design-only`, and `wallpaper-pack` are also supported. Directory inputs are inventoried in stable order, resolved once, and written as PNGs into one fresh task directory.

## Text and language

`prompt` derives sparse copy according to the original brief; `exact` preserves the user's current wording verbatim; `none` forbids letters, numerals, logos, labels, and pseudo-text. Resolve the target language or locale explicitly. The Skill never invents a fixed title or guesses language from filenames.

<!-- xxd-readme-ads:start -->
## About XXD

XXD is Xiaoxiaodong's abbreviated brand name. This project is created and maintained by [@xiaoxiaodong01](https://x.com/xiaoxiaodong01).

## Xiaoxiaodong multi-platform membership · CNY 699/year

> **Advertising disclosure:** The QR code, membership, and paid-service links below are XXD promotional information. Scanning or purchasing is entirely optional and does not affect access to this open-source project.

One annual membership unlocks three benefits together: **Knowledge Planet + the XXD Member Prompt Library + membership for all General Skills**. They are included in one membership; no separate purchase is required.

<!-- xxd-panel-command-system:start -->

### How the Skills work together

| Level | Included | What it does |
|---|---|---|
| **General** | [`xxd-panel-all`](https://github.com/xiaoxiaodong-ai/xxd-panel-all) | Detects available numbered Skills, recommends them by image, theme, or use, and organizes multi-style and batch tasks. |
| **Soldier** | `xxd-panel-NNN` | Each numbered Skill follows its own original brief and aesthetic to complete the specific task assigned by the General. |

<!-- xxd-panel-command-system:end -->

### What you receive

1. **One-to-one WeChat AI learning and project support**
   Add Xiaoxiaodong on WeChat via the QR code below to discuss AI learning, tools, and real projects one to one, with practical guidance and answers. Representative questions may be organized into member resources.
2. **A growing member prompt library**
   The [XXD Member Prompt Library](https://vip.xiaoxiaodong.ai/) currently contains about 32,000 prompts and will keep expanding, with a goal of exceeding 100,000.
3. **All General Skills and usage support**
   One membership covers every General Skill, with usage guidance and Q&A when you need help.
4. **Priority for high-need requests**
   Frequently requested, high-need prompts and Skills are reviewed and developed first where appropriate.

### How to join

- [Activate membership on the member website](https://vip.xiaoxiaodong.ai/).
- Or scan the QR code below to add Xiaoxiaodong on WeChat for one-to-one activation support.

<p align="center"><a href="https://xiaoxiaodong.pages.dev/assets/wechat-qr.png"><img src="https://xiaoxiaodong.pages.dev/assets/wechat-qr.png" alt="Contact Xiaoxiaodong" width="280"></a></p>
<!-- xxd-readme-ads:end -->

## License

This project—including the Skill, prompts, scripts, documentation, and accompanying sample images—is licensed under the **PolyForm Noncommercial License 1.0.0**. See [LICENSE](LICENSE) for the full legal text and <https://polyformproject.org/licenses/noncommercial/1.0.0> for the official page.

In plain language:

- Individuals may use it for study, research, experimentation, testing, hobby projects, and private entertainment. Charities, educational institutions, public research, safety or health organisations, environmental organisations, and government institutions may also use it.
- For **noncommercial purposes**, you may use, copy, modify, create derivative works, and share it. When sharing, you must also provide this license (or the link above) and every `Required Notice:` statement supplied by the author.
- It may not be used in commercial products or services, paid delivery, sale of access or licences, or any use expected to lead to commercial application. Obtain separate written permission from the copyright holder before commercial use.
- The agreement grants only the copyright licence and limited patent licence expressly stated. It grants no trademarks, brand names, or other unstated rights, and you may not sublicense your licence to others.
- After written notice of a violation, you must return to compliance and take practical remedial steps within 32 days, or the licences terminate immediately. A written patent-infringement claim also terminates the patent licence.
- The material is provided “as is”, without warranty to the extent permitted by law. Users bear the risks and potential losses arising from its use.

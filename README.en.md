<div align="center">

# XXD Panel 115｜Pastel Stamp Collage Journal

Rebuild a photograph's core memory as a pastel hand-drawn collage stamp on vintage paper

<a href="README.md">简体中文</a> · <strong>English</strong> · <a href="README.ja.md">日本語</a> · <a href="README.ko.md">한국어</a> · <a href="README.ar.md">العربية</a>

</div>

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

## How the photograph becomes a finished work

```text
preserve photographic reality above → understand theme, relationships, structure, emotion, and metaphor → remove irrelevant detail → rebuild a small stamp-like subject → draw with pastel-crayon lines and sparse paper collage → derive 2–4 colours and separate subject from ground → compose deliberate whitespace → add very little light type
```

## Capabilities and boundaries

Every source is generated independently. Never combine photographs or feed an intermediate, sample, or another Panel's result through a second transformation. The canonical output is a 3:4 portrait with a strict 50:50 top–bottom split; `left-right`, `design-only`, and `wallpaper-pack` are also supported. Directory inputs are inventoried in stable order, resolved once, and written as PNGs into one fresh task directory.

## Text and language

`prompt` derives sparse copy according to the original brief; `exact` preserves the user's current wording verbatim; `none` forbids letters, numerals, logos, labels, and pseudo-text. Resolve the target language or locale explicitly. The Skill never invents a fixed title or guesses language from filenames.

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

<!-- xxd-readme-ads:start -->
## About XXD

XXD is Xiaoxiaodong's abbreviated brand name. Created and maintained by [@xiaoxiaodong01](https://x.com/xiaoxiaodong01).

## Support and membership

> **Advertising disclosure:** QR codes and paid membership/service links in this section are XXD promotional content. Scanning or purchasing is optional and does not affect access to this open-source project.


<!-- xxd-panel-command-system:start -->

All General Skills are included in the CNY 699/year membership; no separate purchase is required.

| Level | Skill | Responsibility |
|---|---|---|
| **General** | [`xxd-panel-all`](https://github.com/xiaoxiaodong-ai/xxd-panel-all) | Detect available numbered Skills; recommend by image, theme, or use; dispatch a chosen number; organize multi-style trials; and assign folders of images to individual jobs. |
| **Soldiers** | `xxd-panel-NNN` | Each numbered Skill executes only its own original brief and aesthetic, completing the individual job assigned by the General. |

<!-- xxd-panel-command-system:end -->

### Knowledge Planet + Member Prompt Library + All General Skills Membership · CNY 699/year

[Knowledge Planet](https://wx.zsxq.com/group/15554814142882), the [XXD Member Prompt Library](https://vip.xiaoxiaodong.ai/), and membership for all General Skills are one membership: **one annual payment unlocks all three benefits, with no second purchase required.**

[Knowledge Planet](https://wx.zsxq.com/group/15554814142882) · [Member Prompt Library](https://vip.xiaoxiaodong.ai/)

<p align="center"><a href="https://xiaoxiaodong.pages.dev/assets/wechat-qr.png"><img src="https://xiaoxiaodong.pages.dev/assets/wechat-qr.png" alt="XXD WeChat" width="280"></a></p>

---

<div align="center">

## Support this open-source project

If this project helps you, you’re welcome to support it through Buy Me a Coffee—entirely optional.

<p align="center"><a href="https://github.com/nevertoday/zhongguo-traditional-colors/blob/main/docs/images/buy-me-a-coffee-qr.png?raw=true"><img src="https://github.com/nevertoday/zhongguo-traditional-colors/blob/main/docs/images/buy-me-a-coffee-qr.png?raw=true" alt="Buy Me a Coffee" width="180"></a></p>

</div>
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

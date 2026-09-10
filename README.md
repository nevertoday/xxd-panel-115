<div align="center">

# XXD Panel 115｜粉彩章印拼贴志

把照片的核心记忆，重构成复古纸张上的粉彩手绘涂鸦章印

<strong>简体中文</strong> · <a href="README.en.md">English</a> · <a href="README.ja.md">日本語</a> · <a href="README.ko.md">한국어</a> · <a href="README.ar.md">العربية</a>

</div>

## 16:9 左右双联样张

以下四张为独立素材，完整 16:9 画布：左为现实摄影，右为本 Panel 设计转译，严格 50:50。文案由模型按原始提示词从当前照片智能生成。

<table>
  <tr>
    <td width="50%"><img src="./assets/examples/sample-05.png" alt="XXD Panel 115 样张 5"></td>
    <td width="50%"><img src="./assets/examples/sample-06.png" alt="XXD Panel 115 样张 6"></td>
  </tr>
  <tr>
    <td width="50%"><img src="./assets/examples/sample-07.png" alt="XXD Panel 115 样张 7"></td>
    <td width="50%"><img src="./assets/examples/sample-08.png" alt="XXD Panel 115 样张 8"></td>
  </tr>
</table>

## 3:4 上下双联样张

以下四张使用与 16:9 组完全不同的四张独立素材，重新生成完整 3:4 上下双联画布；上部保留现实摄影，下部遵循本 Panel 原始提示词重构。英文配字只从当前照片的内容、情绪或隐喻中生成。

<table>
  <tr>
    <td width="50%"><img src="./assets/examples/sample-09.png" alt="XXD Panel 115 新增上下样张 1"></td>
    <td width="50%"><img src="./assets/examples/sample-10.png" alt="XXD Panel 115 新增上下样张 2"></td>
  </tr>
  <tr>
    <td width="50%"><img src="./assets/examples/sample-11.png" alt="XXD Panel 115 新增上下样张 3"></td>
    <td width="50%"><img src="./assets/examples/sample-12.png" alt="XXD Panel 115 新增上下样张 4"></td>
  </tr>
</table>


## 适用场景与解决的问题

当照片需要重新设计成海报、封面、社交内容或展览图像时，常见问题是把照片逐物描摹、塞满画面，或套上甜腻的儿童拼贴模板，导致主体关系和呼吸感消失。

**Panel 115** 将每张照片单独制作成 3:4 竖版海报：上半部分完整保留原始照片，下半部分把最值得记住的主题、关系、结构走势、情绪和隐喻，重构成复古纸张肌理上的粉彩手绘涂鸦材料拼贴插画。小尺度章印式主体、大面积有意识留白、2–4 种源图鲜活色彩与极少量轻型打字排版，共同完成巧妙而轻盈的再表达。

它解决主体被逐物复制、背景与主体糊成一团、画面填满、写实描摹、光滑矢量、过度装饰、儿童模板感、3D 感和商业海报感等问题。

## 使用窍门

- **先给一张清楚的照片：** 先选一张主体、动作和关系都容易辨认的图，再决定输出方式与比例。
- **一句话串起参数：** 直接说“上下对照 / 左右对照 / 纯设计 + 16:9 / 3:4 / 手机壁纸”，也可以补充电脑、平板或电子手表尺寸。
- **把必须保留的内容说清楚：** 指定人物、物件、动作、关系和文字；避免同时规定过多布局细节，让风格有空间完成设计。
- **文字有三种选择：** 让模型按图片智能生成、用 `--text exact --copy` 锁定逐字文案，或用 `--text none` 完全不要文字。
- **说明现实区与设计区：** 上下或左右对照时，注明哪一侧保留照片、哪一侧负责设计转译；纯设计和壁纸则说明整张画布都要重新设计。
- **先单张试，再批量做：** 先用一张图确认模式、比例、文字和语言，再把同一套参数用于目录批处理；每轮只改一个变量，结果更容易比较。

## 开始使用

```bash
git clone https://github.com/nevertoday/xxd-panel-115.git
mkdir -p ~/.codex/skills
ln -s "$(pwd)/xxd-panel-115" ~/.codex/skills/xxd-panel-115
```

也可以直接使用 `npx skills` 安装：

```bash
npx skills add https://github.com/nevertoday/xxd-panel-115 --skill xxd-panel-115
```

需要用户级 Codex 安装时，可追加 `--global --agent codex --yes`。安装后重新启动 Agent 会话，然后调用 `$xxd-panel-115`。

## 原始提示词 · 五种语言

[简体中文](references/original-prompt/zh-CN.md) · [English](references/original-prompt/en.md) · [日本語](references/original-prompt/ja.md) · [한국어](references/original-prompt/ko.md) · [العربية](references/original-prompt/ar.md)

简体中文文件逐字保存用户提供的原始提示词，是运行时唯一的创作与审美权威；其他四个版本是完整、忠实的阅读译文，不会反过来改写生图提示词。

**关键词：** 3:4 严格 50:50 · 复古纸张肌理 · 粉彩蜡笔涂鸦 · 材料拼贴 · 小尺度章印 · 2–4 色源图取色 · 有意识留白 · 轻型打字排版

## 快速判断：Panel 115 适合你吗？

| 你关心的问题 | 这套风格的回答 |
|---|---|
| 想要上下对照但不想做成普通滤镜？ | 上部保留真实照片，下部独立重构为纸面粉彩拼贴，严格各占 50%。 |
| 担心设计区太满或主体变得不可辨？ | 只保留核心轮廓、姿态、方向和关系，以小尺度章印与大面积留白组织画面。 |
| 想要柔和鲜活而非廉价糖果色？ | 从上方照片提取 2–4 种代表性色彩，重新调制为清晰、温暖的粉彩组。 |

## 完整能力与边界

每张源图独立生成，不拼接多张照片，不把中间图、样张或其他 Panel 成品再次送入模型。标准输出为 3:4 竖版、上下严格 50:50；同时支持 `left-right`、`design-only` 与 `wallpaper-pack`。目录输入会递归扫描常见位图，统一解析设置，并把所有 PNG 直接写入同一个新任务目录。

## 文字与语言

`prompt` 模式按原始提示词从照片提炼少量文字；`exact` 模式逐字使用本次提供的文案；`none` 模式禁止字母、数字、Logo、标签和伪文字。需明确目标语言或地区，Skill 不预写固定标题，也不从文件名猜测语言。

<!-- xxd-readme-ads:start -->
## 关于 XXD

XXD 是小小东品牌名的缩写，本项目由小小东创建并维护：[@xiaoxiaodong01](https://x.com/xiaoxiaodong01)。

## 小小东多端会员 · 699 元/年

> **广告与商业信息声明：** 以下二维码、会员与付费服务链接属于小小东的广告信息。是否扫码或购买完全自愿，不影响本开源项目的访问与使用。

一次年费，同时开通三项会员权益：**知识星球 + 小小东成员提示词库 + 全部 将军总指挥 Skills 会员**。三项权益合并在同一份会员中，无需分别购买。

<!-- xxd-panel-command-system:start -->

### Skills 如何协作

| 层级 | 包含内容 | 用途 |
|---|---|---|
| **General** | [`xxd-panel-all`](https://github.com/xiaoxiaodong-ai/xxd-panel-all) | 识别可用的编号 Skills，按图片、主题和用途推荐，并组织多风格试稿与批量任务。 |
| **Soldier** | `xxd-panel-NNN` | 每个编号执行自己的原始提示词与审美，完成 General 分派的具体任务。 |

<!-- xxd-panel-command-system:end -->

### 会员权益

1. **微信一对一 AI 学习与项目答疑**
   扫描下方二维码，添加小小东微信，围绕 AI 学习、工具使用和实际项目进行一对一沟通，获得答疑与建议；代表性问题将整理为会员内容。
2. **持续更新的成员提示词库**
   [小小东成员提示词库](https://vip.xiaoxiaodong.ai/)当前约有 3.2 万条提示词，会持续整理和扩充，目标超过 10 万条。
3. **全部 将军总指挥 Skills 与使用答疑**
   一份会员覆盖全部 将军总指挥 Skills；使用过程中遇到问题，可以获得相应的使用说明与答疑。
4. **高频刚需优先处理**
   会员提出的高频、刚需提示词与 Skills 需求，会优先评估和开发。

### 如何开通

- 可在[成员网站](https://vip.xiaoxiaodong.ai/)自助开通。
- 也可以扫描下方二维码，添加小小东微信，进行一对一沟通并获得开通协助。

<p align="center"><a href="https://xiaoxiaodong.pages.dev/assets/wechat-qr.png"><img src="https://xiaoxiaodong.pages.dev/assets/wechat-qr.png" alt="联系小小东" width="280"></a></p>
<!-- xxd-readme-ads:end -->

## 许可证

本项目（包括 Skill、提示词、脚本、文档及随附样张）采用 **PolyForm Noncommercial License 1.0.0**。完整法律条文请见 [LICENSE](LICENSE)，官方页面见 <https://polyformproject.org/licenses/noncommercial/1.0.0>。

用人话说：

- 个人可以用于学习、研究、实验、测试、兴趣项目和私人娱乐；慈善机构、教育机构、公共研究/安全/卫生机构、环保组织及政府机构也可以使用。
- 在**非商业目的**下，你可以使用、复制、修改、制作衍生作品并分享；分享时必须同时提供本许可证（或上面的链接）以及作者提供的所有 `Required Notice:` 声明。
- 不允许用于商业产品或服务、收费交付、出售访问权或许可，或任何预期会带来商业应用的用途。需要商业使用时，请先向版权方另行取得书面许可。
- 本协议只授予其中明确写出的著作权许可和有限的专利许可，不授予商标、品牌名称或其他未明确授予的权利，也不能把你的许可再转授给他人。
- 如果收到书面违约通知，须在 32 天内纠正并采取实际补救措施，否则许可会立即终止；就专利侵权提出书面主张也会终止专利许可。
- 内容按“现状”提供，在法律允许的范围内不作任何担保，使用风险和可能的损失由使用者自行承担。

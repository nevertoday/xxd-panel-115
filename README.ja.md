<div align="center">

# XXD Panel 115｜パステル印章コラージュ帖

写真の核となる記憶を、古紙の上のパステル手描き印章コラージュへ再構成する

<a href="README.md">简体中文</a> · <a href="README.en.md">English</a> · <strong>日本語</strong> · <a href="README.ko.md">한국어</a> · <a href="README.ar.md">العربية</a>

</div>

## 作例展示

**16:9 横長・左右構成（左が元写真、右がデザイン、厳密な 50:50）**

| sample-05 | sample-06 |
|---|---|
| ![XXD Panel 115 横長作例 1](assets/examples/sample-05.png) | ![XXD Panel 115 横長作例 2](assets/examples/sample-06.png) |
| ![XXD Panel 115 横長作例 3](assets/examples/sample-07.png) | ![XXD Panel 115 横長作例 4](assets/examples/sample-08.png) |

**3:4 縦長・上下構成（上が元写真、下がデザイン、厳密な 50:50）**

| sample-09 | sample-10 |
|---|---|
| ![XXD Panel 115 縦長作例 1](assets/examples/sample-09.png) | ![XXD Panel 115 縦長作例 2](assets/examples/sample-10.png) |
| ![XXD Panel 115 縦長作例 3](assets/examples/sample-11.png) | ![XXD Panel 115 縦長作例 4](assets/examples/sample-12.png) |

上の8点は異なるオリジナル参考画像を使用し、Panel 115 が自身の原文プロンプトから1点ずつ独立して単一パスで生成しました。別番号の作品や中間結果は流用していません。すべての作例から AI 生成・来歴メタデータを削除済みです。

## 適した場面と解決すること

写真をポスター、表紙、SNS、展示画像へ再設計するとき、全てを逐物描写したり画面を埋めたり、甘い子ども向けコラージュの型を当てたりして、元の関係と呼吸を失いがちです。

**Panel 115** は写真一枚を独立した 3:4 縦長ポスターにします。上半分は写真の現実を保ち、下半分は記憶に残るテーマ、関係、構造の流れ、感情、視覚的比喩を、古紙の質感を持つパステル手描き素材コラージュへ翻訳します。小さな印章の主役、意識的な余白、元写真から選ぶ2〜4色、控えめな軽い文字が、巧みで軽やかな再表現をつくります。

## 使い方のコツ

- **まず一枚の見やすい写真から始める：** 主体・動作・関係が分かる画像を選んでから、出力形式と比率を決めます。
- **パラメータを一文でつなぐ：** 「上下 / 左右 / デザインのみ + 16:9 / 3:4 / スマホ壁紙」のように指定し、PC・タブレット・スマートウォッチのサイズも追加できます。
- **残したい内容を明示する：** 人物、物、動作、関係、文字を指定し、レイアウトを細かく縛りすぎずスタイルに任せます。
- **文字の方法を選ぶ：** 画像から自動生成、`--text exact --copy` で逐字固定、または `--text none` で文字なしにできます。
- **写真領域とデザイン領域を伝える：** 上下・左右では写真を残す側と再設計する側を指定し、デザインのみ・壁紙では全画面を再設計すると伝えます。
- **一枚で試してから一括処理する：** モード、比率、文字、言語を一枚で確認し、同じ設定をフォルダに適用します。比較しやすいよう一度に一つだけ変更します。

## 使い方

```bash
git clone https://github.com/nevertoday/xxd-panel-115.git
mkdir -p ~/.codex/skills
ln -s "$(pwd)/xxd-panel-115" ~/.codex/skills/xxd-panel-115
```

または：

```bash
npx skills add https://github.com/nevertoday/xxd-panel-115 --skill xxd-panel-115
```

ユーザー単位の Codex には `--global --agent codex --yes` を追加し、Agent セッションを再起動して `$xxd-panel-115` を呼び出します。

## 原文プロンプト・5言語

[简体中文](references/original-prompt/zh-CN.md) · [English](references/original-prompt/en.md) · [日本語](references/original-prompt/ja.md) · [한국어](references/original-prompt/ko.md) · [العربية](references/original-prompt/ar.md)

中国語ファイルはユーザーの原文を一字一句保存した唯一の創作・美的基準です。他の4ファイルは忠実な全文訳で、生成プロンプトを書き換えません。

**キーワード：** 3:4 厳密 50:50 · 古紙テクスチャ · パステルクレヨン落書き · 素材コラージュ · 小さな印章主体 · 元写真由来2〜4色 · 意識的な余白 · 軽いタイプ文字

## Panel 115 が向いているか

| 必要なこと | このスタイルの答え |
|---|---|
| フィルターではない上下比較ポスター | 上に現実写真、下に紙とパステルの再構成を各50%で配置。 |
| 混雑さを抑えた認識可能な主体 | 輪郭、姿勢、方向、関係を絞り、小さな印章と大きな余白で構成。 |
| 安価なキャンディ色ではない柔らかな色 | 写真から2〜4色を選び、明るく温かなパステルへ再調整。 |

## 能力と境界

各写真を独立生成し、複数写真や中間生成物、作例、別 Panel の結果を再変換しません。標準は3:4縦長・上下厳密50:50で、`left-right`、`design-only`、`wallpaper-pack` にも対応します。ディレクトリ入力は安定順で一覧化し、設定を一度解決して、PNGを一つの新しいタスクディレクトリへ出力します。

## 文字と言語

`prompt` は原文に従って少量の文を導き、`exact` は今回の文言を一字一句保持し、`none` は文字・数字・Logo・擬似文字を禁止します。対象言語を明示し、ファイル名から推測しません。

<!-- xxd-readme-ads:start -->
## XXD について

XXD は Xiaoxiaodong のブランド名略称です。本プロジェクトの作成・管理：[@xiaoxiaodong01](https://x.com/xiaoxiaodong01)。

## Xiaoxiaodong マルチプラットフォーム会員 · 年額 CNY 699

> **広告表示：** 以下のQRコード、会員および有料サービスのリンクはXXDの広告情報です。スキャンや購入は任意であり、オープンソースの利用には影響しません。

年額会員ひとつで、**Knowledge Planet＋XXD会員プロンプトライブラリ＋すべてのGeneral Skills会員**の3つを利用できます。別々に購入する必要はありません。

<!-- xxd-panel-command-system:start -->

### Skills の連携方法

| 区分 | 含まれるもの | 役割 |
|---|---|---|
| **General** | [`xxd-panel-all`](https://github.com/xiaoxiaodong-ai/xxd-panel-all) | 利用可能な番号付きSkillsを検出し、画像・テーマ・用途から推薦し、複数スタイルや一括タスクを整理します。 |
| **Soldier** | `xxd-panel-NNN` | 各番号が固有の原文プロンプトと美学に従い、Generalから割り当てられた具体的な作業を完成させます。 |

<!-- xxd-panel-command-system:end -->

### 会員の内容

1. **XiaoxiaodongをAI学習の相談相手に**
   [Knowledge Planet](https://wx.zsxq.com/group/15554814142882)で、AI学習、ツール、実際のプロジェクトについていつでも質問できます。回答や役立つ内容を会員向けに整理していきます。
2. **継続更新する会員プロンプトライブラリ**
   [XXD会員プロンプトライブラリ](https://vip.xiaoxiaodong.ai/)には現在約3.2万件のプロンプトがあり、10万件超を目標に継続して拡充します。
3. **すべてのGeneral Skillsと利用サポート**
   ひとつの会員で全General Skillsを利用でき、使い方に困ったときは案内やQ&Aを受けられます。
4. **必要性の高い要望を優先**
   会員から寄せられた頻度と必要性の高いプロンプトやSkillsは、優先して検討・開発します。

### 開設方法

- [会員サイトから自分で開設](https://vip.xiaoxiaodong.ai/)できます。
- または下のQRコードからXiaoxiaodongに連絡し、開設を依頼できます。

<p align="center"><a href="https://xiaoxiaodong.pages.dev/assets/wechat-qr.png"><img src="https://xiaoxiaodong.pages.dev/assets/wechat-qr.png" alt="Xiaoxiaodongへの連絡" width="280"></a></p>
<!-- xxd-readme-ads:end -->

## ライセンス

本プロジェクト（Skill、プロンプト、スクリプト、文書、付属サンプル画像を含む）は **PolyForm Noncommercial License 1.0.0** の下で提供されます。完全な法的条文は [LICENSE](LICENSE)、公式ページは <https://polyformproject.org/licenses/noncommercial/1.0.0> を参照してください。

分かりやすく言うと：

- 個人は学習、研究、実験、テスト、趣味のプロジェクト、私的娯楽に使用できます。慈善団体、教育機関、公的研究・安全・保健機関、環境保護団体、政府機関も使用できます。
- **非商業目的**であれば、使用、複製、変更、派生物の作成、共有が可能です。共有時には本ライセンス（または上記リンク）と、作者が示したすべての `Required Notice:` 文を添付する必要があります。
- 商用製品・サービス、有料納品、アクセス権やライセンスの販売、商業利用につながることが予想される用途には使用できません。商用利用には著作権者から別途書面による許可を得てください。
- 本契約が付与するのは明記された著作権ライセンスと限定的な特許ライセンスだけです。商標、ブランド名、その他明記されていない権利は付与されず、ライセンスを第三者へ再許諾することもできません。
- 書面で違反通知を受けた場合、32 日以内に遵守状態へ戻り、実際の是正措置を取らなければライセンスは直ちに終了します。特許侵害を書面で主張した場合も特許ライセンスが終了します。
- 内容は法律が認める範囲で「現状のまま」提供され、保証はありません。利用に伴うリスクと損失は利用者が負います。

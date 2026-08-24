<p align="center"><img src="./assets/banner.svg" alt="XXD Panel 051 project banner" width="1200"></p>

<div align="center">

# 🦁 XXD Panel 051

### 写真の関係性を、軽く触れられそうな紙のミニチュアへ

[![Codex Skill](https://img.shields.io/badge/Codex-Skill-000000?style=flat-square)](./SKILL.md)
[![Modes](https://img.shields.io/badge/Modes-4-D5898C?style=flat-square)](#)
[![Output](https://img.shields.io/badge/Output-PNG-6FA4B7?style=flat-square)](#)

<a href="README.md">简体中文</a> · <a href="README.en.md">English</a> · <strong>日本語</strong> · <a href="README.ko.md">한국어</a> · <a href="README.ar.md">العربية</a>

</div>

> ミニチュア紙工芸 · 横長の浮遊景観帯 · 手仕事の証拠 · エアリーブルー · 大きな余白

元写真の最も識別しやすい主題と物語的な関係を、手作りのミニチュア紙工芸へ変換します。見分けられる中心模型、細長く軽い横方向の景観帯、根拠のある少数の脇役模型、紙繊維、そして広い淡色紙面で構成します。

## 美的ロジック

```text
主題・輪郭・姿勢・物語関係を固定 → 固有の手掛かりを3つ残す → 識別できる手作りミニチュアを再構築 → 必要な脇役模型だけを抽出 → 細長い横方向の浮遊景観帯に配置 → 紙繊維・折り目・切り口・層の厚み・小さな誤差を見せる → 柔らかなマクロ光で体積を作る → 広い淡色紙面を残す → 文字を作品署名のように統合
```

無関係な写真へ差し替えても識別性、模型構造、素材選択、景観帯のリズム、配色、文案が変わらないなら、この Panel には属しません。

## ビジュアル契約

- 固有の手掛かりを最低3つ保ち、中心の手作り模型を一目で識別できるようにします。
- 一つの中心主題と細長い横方向の浮遊景観帯だけを作り、脇役模型は元写真に根拠を持たせて小さく静かにします。
- 尺度差、層状の遮蔽、小さな前景・背景で奥行きを作り、中央配置でも硬い左右対称や厚い台座を避けます。
- 紙繊維、折り端、切り口、層の厚み、毛羽、接合部、小さな制作誤差を、柔らかな拡散マクロ光の下で見せます。
- 空気感のある青を、アイボリー、クリーム、淡いベージュ、灰緑、セージ、建築的中間色で整えます。くすんだローズは小さな点だけです。
- プラスチックCG、玩具展示、幼い工作、汎用ジオラマ、過密、過度な可愛さ、EC商品展示、平面ベクター代用、濁りや黄ばみを拒否します。

完全仕様は [SKILL.md](SKILL.md) と [生成プロンプト](references/xxd-panel-051-prompt.en.md) を参照してください。原文の美的動機を守りつつ、歴史的な3:4画布を隠れた既定値にはしません。

## 作例 · X より

> [小小東（@xiaoxiaodong01）](https://x.com/xiaoxiaodong01/status/2091470045973262409) · 2026年8月23日<br>
> GPT2 × 切り紙 × 盆景 × 上質感 × 美学プロンプト × VOL.051

<table>
  <tr>
    <td width="50%"><a href="https://x.com/xiaoxiaodong01/status/2091470045973262409"><img src="./assets/examples/sample-01.jpg" alt="XXD Panel 051 作例 1"></a></td>
    <td width="50%"><a href="https://x.com/xiaoxiaodong01/status/2091470045973262409"><img src="./assets/examples/sample-02.jpg" alt="XXD Panel 051 作例 2"></a></td>
  </tr>
  <tr>
    <td width="50%"><a href="https://x.com/xiaoxiaodong01/status/2091470045973262409"><img src="./assets/examples/sample-03.jpg" alt="XXD Panel 051 作例 3"></a></td>
    <td width="50%"><a href="https://x.com/xiaoxiaodong01/status/2091470045973262409"><img src="./assets/examples/sample-04.jpg" alt="XXD Panel 051 作例 4"></a></td>
  </tr>
</table>

<p align="center"><a href="https://x.com/xiaoxiaodong01/status/2091470045973262409">元の投稿と完全なプロンプトを見る →</a></p>

これらの作例は 051 の美的意図を示すものであり、作例の被写体、構図、配色、コピー、旧キャンバス比率が生成時の参照や現在の既定値になることはありません。

## 組み合わせ可能な4つの出力

`1`、`1+3`、`1,2,4`、`全部` で一つまたは複数を選べます。`全部` は元画像ごとに7点の独立PNGを出力します。モード選択後、生成前に完成画像全体の画角を必ず確認します：元プロンプトの `3:4`、明示的な元画像比率、一般的な比率、またはカスタム比率／正確なピクセルです。元画像寸法を暗黙には適用しません。

| モード | 画角ルール | 成果物 |
| --- | --- | --- |
| `top-bottom` | ユーザー確認済みの完成画角 | 完成キャンバスを一度に生成：上に高忠実度の元画像、下に 051 デザイン、約50/50 |
| `left-right` | ユーザー確認済みの完成画角 | 完成キャンバスを一度に生成：左に高忠実度の元画像、右に 051 デザイン、約50/50 |
| `design-only` | ユーザー確認済みの完成画角 | 051 デザインが全画面を満たし、元画像は表示しない |
| `wallpaper-pack` | 端末ごとに確認 | スマートフォン、iPad、デスクトップ、子ども用ウォッチの個別PNG |

二連モードは元画像を高忠実度の編集／参照入力として使い、完全なスタイルプロンプト一式で完成画面を直接生成します。写真、デザイン、色、光、文字、意味を一体化するためです。決定論的な合成は、完成画面の再試行後も失敗した場合、原画像のピクセル完全保持を明示された場合、生成経路が指定画角に対応しない場合、または無劣化の最終ピクセル調整が必要な場合だけ使います。

壁紙は連動または独立を選べます。連動はiPad基準作を一つ承認し、他の端末を元画像＋同じ基準作から個別に再構成します。独立は各端末が元画像だけを参照します。どちらも他端末の成果を切り抜かず、派生を連鎖しません。

## 文案、ラスター、信頼

生成前に自動文案、完全指定文案、文字なしを確認します。原稿は歴史的に英語題名へ触れていますが、英語を既定にせず対象読者の言語に従います。自動文案は場所、主題の固有性、テーマ、感情、深意、隠れた関係から短い題名を作ります。小さく精緻でわずかに手書き感のある文字を景観帯の下や基座沿いに置き、商業見出しでなく制作者の署名のように統合します。

通常サイズは元画像に適応し、ペアは厳密に50/50、成果物はすべてPNGです。毎回 `~/Desktop/xxd/xxd-panel-051/` に新しいタスクを作成します。画像生成経路は秘匿情報を表示せず、SVG、HTML、Canvas、プログラム描画は代替になりません。

## 選択式 UI とインラインパラメータ

実行環境に本物の対話コントロールがある場合、カード式の選択を優先します。出力モードと通常画像サイズは複数選択、文案方式と壁紙の関係は単一選択です。サイズは自動調整、元画像比率、1:1、3:4、4:3、4:5、5:4、2:3、3:2、9:16、16:9、21:9、5:7、7:5、カスタム比率／ピクセルから選べます。対話コントロールがない環境では、クリックできない疑似チェックボックスではなく、読みやすい複数行の番号メニューに切り替えます。

すべての設定は呼び出し後の変数として直接指定できます。

```text
/xxd-panel-051 photo.jpg --mode top-bottom,design-only --size auto,3:4,9:16 --text auto --locale ja-JP
```

`--mode`、複数指定可能な `--size`、`--text auto|custom|none`、`--locale`、`--copy`、`--wallpaper linked|independent`、`--wallpaper-size`、`--out` に対応します。必要な値が揃っていれば質問を省略して生成を開始し、不足分だけを追加で尋ねます。異なる縦横比はそれぞれ再構成し、四端末壁紙は通常サイズと機械的に掛け合わせない独立分岐です。

## 画像モデルの優先順位

GPT Image 2 を既定の第一候補とします。高忠実度の参照画像、生成前の完成キャンバス確認、二連モードの完成画面一括生成、条件を満たした場合だけのスクリプト合成という既存の流れは変わりません。

現在のツールまたは設定済み経路から実際に利用でき、元画像の忠実度、完成画角、対象言語の文字、連動壁紙の複数参照を満たせる場合は、Seedance 5.0 Pro、Nano Banana Pro（Gemini Image Pro）、Nano Banana 2（Gemini Image Flash）、その他の互換ビットマップモデルも利用できます。代替モデルが変更できるのは生成経路だけで、モード、画角、文案、言語、壁紙関係、完成キャンバス優先の方針は変更できません。

適切な経路がない場合は、画像生成ツールを有効にするか API Key を提供するようユーザーに案内します。ユーザーが提供した認証情報は現在のタスクで利用できますが、返信やログに再表示・記録・開示しません。明示的な依頼がない限り、長期保存やプロバイダー、アカウント、課金、グローバル経路の設定変更も行いません。

## 使い始める

```bash
git clone https://github.com/nevertoday/xxd-panel-051.git
mkdir -p ~/.codex/skills
ln -s "$(pwd)/xxd-panel-051" ~/.codex/skills/xxd-panel-051
```

Claude Code では同じフォルダを `~/.claude/skills/xxd-panel-051` にリンクできます。インストール後にセッションを再起動してください。

完全仕様：[Skill](SKILL.md) · [原始資料](references/051-source.md) · [英語プロンプト](references/xxd-panel-051-prompt.en.md) · [中国語プロンプト](references/xxd-panel-051-prompt.zh-CN.md)

## XXD とサポート

XXD は小小東のブランド名の略称です。作者：[@xiaoxiaodong01](https://x.com/xiaoxiaodong01)。個別相談は299元／時間、Skills ユーザー交流グループは一回払い99元です。Knowledge Planet＋会員プロンプトライブラリは年額699元の一回の支払いで両方を利用できます。[Knowledge Planet](https://wx.zsxq.com/group/15554814142882) から加入した場合は WeChat で小小東に連絡して[プロンプトライブラリ](https://vip.xiaoxiaodong.ai/)の引換コードを受け取り、プロンプトライブラリで自動開通した場合は WeChat で連絡して Knowledge Planet への招待を受けてください。[WeChat](https://xiaoxiaodong.pages.dev/assets/wechat-qr.png)

<p align="center"><a href="https://xiaoxiaodong.pages.dev/assets/wechat-qr.png"><img src="https://xiaoxiaodong.pages.dev/assets/wechat-qr.png" alt="XXD WeChat" width="280"></a></p>

<div align="center"><strong>写真を玩具にするのではなく、その本当の関係を紙へ折り込む。</strong></div>

---

<div align="center">

## ☕ オープンソースを支援

支援は任意で、プロジェクトへのアクセス条件を変えません。

<p align="center"><a href="https://github.com/nevertoday/zhongguo-traditional-colors/blob/main/docs/images/buy-me-a-coffee-qr.png?raw=true"><img src="https://github.com/nevertoday/zhongguo-traditional-colors/blob/main/docs/images/buy-me-a-coffee-qr.png?raw=true" alt="Buy Me a Coffee" width="180"></a></p>

</div>

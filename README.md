# IC2 Classical

**IndustrialCraft 2（IC²）v1.95b（Minecraft 1.2.5）を、Minecraft 1.21.1 / NeoForge 向けに再実装した非公式の移植版**です。

原作：**Industrial Craft（IC²）** — https://www.curseforge.com/minecraft/mc-mods/industrial-craft

## 原作への準拠

- 本 Mod の仕様は **元祖 IndustrialCraft 2 v1.95b に準拠** しています。電力網（EU）の配電・損失・過負荷、機械の消費電力・加工時間・容量、
  発電量、原子炉の熱計算、作物の成長・交配、レシピ、GUI の配置などは、原作の数値と処理を基準に作り直しています。
- 1.21.1 に存在しない仕組み（数値 ID、ModLoader 時代の API など）は、同じ遊び方になるよう 1.21.1 の仕組みへ置き換えています。
  原作と完全には同じにできなかった点・未実装の点は、移行状況資料（`MIGRATION_STATUS.md`）にまとめています。
- 原作の設定ファイル（`IC2.cfg`）の項目は、`config/ic2_classical-common.toml` に引き継いでいます（既定値は原作と同じ）。

## 非公式であること・権利について

- 本 Mod は **非公式** の移植版で、原作の開発チーム（CurseForge 上のオーナー sfPlayer1、作者 Aroma1997・Chocohead ほか）とは関係がなく、
  原作チームの承認・支援を受けたものではありません。本 Mod についての問い合わせを原作チームへ送らないでください。
- 「IndustrialCraft」「IC²」の名称、原作の設計・テクスチャなどの権利は、原作の権利者に帰属します。
  原作の CurseForge ページに表示されているライセンスは **All Rights Reserved** です。
- 本 Mod のテクスチャには、原作 v1.95b のスプライト画像を切り出したものを使っています。

## ソースコードの公開について

本 Mod の **ソースコードは GitHub などで公開していません**。配布は jar ファイルのみです。

本 Mod 自体のライセンスは **All Rights Reserved** です。jar の再配布・改変・逆コンパイルした内容の公開はご遠慮ください。

## 動作環境

| 項目 | 内容 |
|---|---|
| Minecraft | 1.21.1 |
| Mod ローダー | NeoForge 21.1 系（21.1.266 で開発） |
| Java | 21 |
| 任意 | JEI 19.70.0 以降（機械レシピの表示） |

## 他 Mod との連携

- **JEI**（任意）：粉砕機・抽出機・圧縮機のレシピを表示します。鉄製かまど・電気炉・誘導炉は精錬レシピの機械として表示されます。
- **アイテムの自動搬入・搬出**：機械のインベントリを NeoForge 標準の方式で公開しています。BuildCraft 系のアイテムパイプやホッパーなどが接続し、
  原作と同じ「面ごとのスロット」（例：加工機械は 上面＝入力、下面＝電池、側面＝出力）で搬入・搬出できます。特定の Mod への依存はありません。

## 変更履歴

`CHANGELOG.md` を参照してください。

---

## English

**IC2 Classical** is an **unofficial** reimplementation of **IndustrialCraft 2 (IC²) v1.95b** (Minecraft 1.2.5) for Minecraft 1.21.1 / NeoForge.

- Original mod: https://www.curseforge.com/minecraft/mc-mods/industrial-craft
- Gameplay, numbers and mechanics follow the original IC2 v1.95b. Differences and unimplemented features are listed in `MIGRATION_STATUS.md` (Japanese).
- This project is not affiliated with or endorsed by the original IC2 team. All rights to the IndustrialCraft name, design and artwork belong to their respective owners
  (the original mod is listed as "All Rights Reserved" on CurseForge). Textures are taken from the original v1.95b sprites.
- **The source code of this mod is not published** (no GitHub repository). Only the jar is distributed. This mod is "All Rights Reserved";
  please do not redistribute, modify, or publish decompiled code.
- Requirements: Minecraft 1.21.1, NeoForge 21.1.x, Java 21. Optional: JEI 19.70.0+.

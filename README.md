# YESグループ横浜 求人LP群

## プロジェクト概要
YESグループ横浜（風俗求人）のターゲット別ランディングページ群。SEO最適化・構造化データ・レスポンシブデザインを実装した5ページ構成。

## ページ一覧・ターゲット

| ファイル | ターゲット層 | 主要キーワード | 推定文字数 |
|--------|----------|------------|---------|
| `index.html` | 未経験・初心者 | 横浜 初心者向け風俗 未経験 求人 | 約10,000〜12,000字 |
| `lp2.html` | 40代・50代・熟女・人妻 | 横浜 40代 ヘルス 求人 | 約10,000〜12,000字 |
| `lp3.html` | 出稼ぎ・地方在住・短期集中 | 横浜 出稼ぎ 風俗 寮完備 | 約9,000〜11,000字 |
| `lp4.html` | コンセプト・コスプレ好き | 横浜 メイド・OL・高級・ソフトヘルス 求人 | 約11,000〜13,000字 |
| `lp5.html` | 男性スタッフ正社員 | 横浜 風俗店 男性スタッフ 正社員 | 約8,000〜10,000字 |

## 公開URL（本番）
- メインサイト: https://www.kyujin-yes.com/yokohama/
- lp3 canonical: https://www.kyujin-yes.com/yokohama/dekasegi/
- lp4 canonical: https://www.kyujin-yes.com/yokohama/concept/
- GitHub Pages テスト: https://alluxe-hash.github.io/yes-yokohama-recruit-lp/

## 実装済み機能

### SEO対策
- [x] 各ページのmeta title・description・canonical URL
- [x] 構造化データ（JobPosting・FAQPage・LocalBusiness・BreadcrumbList）
- [x] Open Graph・Twitter Card
- [x] ローカルSEO（geo tags・住所・座標）
- [x] H1〜H3見出し階層（キーワード含有）
- [x] 内部リンク（フッターに関連ページリンク）

### コンテンツ（2026年4月改訂・大幅拡充版）
- [x] FAQ: 全ページ6〜10問、各問の回答文が200〜400字（詳細・具体的）
- [x] スタッフインタビュー: 全ページ3〜4名、各300〜400字の長文体験談
- [x] COLUMNセクション: 全ページ3コラム（各400〜600字）追加
- [x] 地域情報セクション: index.html・lp2.html（横浜・曙町エリア情報）
- [x] 収入シミュレーション表（全ページ）
- [x] 体験入店の流れ（5ステップ）
- [x] 店舗紹介（店舗ごとの詳細情報・画像プレースホルダー）
- [x] 職場環境ギャラリー（画像プレースホルダー6枚）

### デザイン
- [x] レスポンシブ（@media max-width:600px 対応）
- [x] フローティングCTA（スクロール後に出現）
- [x] FAQ アコーディオン（JavaScript）
- [x] 画像プレースホルダー（差し替え用枠・説明テキスト付き）
- [x] CSS Gridによるメリット・店舗・インタビュー一覧
- [x] 手作り感のあるデザイン（ノートブック風メリットカード・斜めグラデーション等）

## データモデル・構造化データ

### JobPosting（各ページ）
```json
{
  "title": "横浜 未経験・初心者向け 風俗求人 キャスト（体験入店）",
  "hiringOrganization": { "name": "YESグループ横浜" },
  "jobLocation": "横浜市中区曙町",
  "baseSalary": { "minValue": 30000, "unitText": "DAY" },
  "employmentType": "PART_TIME"
}
```

### LocalBusiness（店舗別）
- eroina（エロいーな）: https://yesgrp.com/yokohama/eroina/
- あわほたる: https://kanto.qzin.jp/awhotaru/
- 螢（ほたる）: https://kanto.qzin.jp/renaissance/

## SEO改善履歴

### 2026年4月（大幅コンテンツ拡充）
- **FAQ拡充**: 各ページ6〜10問、各回答200〜400字（旧：50〜80字）
- **インタビュー長文化**: 各300〜400字（旧：50〜80字）
- **COLUMNセクション追加**: 全5ページに3コラムずつ追加（各400〜600字）
- **地域情報追加**: index.html・lp2.html にローカルSEO強化セクション
- **lp4.htmlインタビューセクション追加**: 3名の体験談新設
- **lp3.htmlインタビュー**: 3名→4名に増加・長文化

## 推定SEOスコア（改訂後）

| 指標 | 改訂前 | 改訂後目標 |
|------|--------|---------|
| 本文文字数 | 3,000〜5,500字 | 8,000〜13,000字 |
| FAQ問数 | 4〜6問 | 6〜10問 |
| FAQ回答文字数 | 50〜80字 | 200〜400字 |
| 総合SEOスコア推定 | 78〜85点 | 88〜93点 |
| 上位表示期待順位 | 20〜50位 | 5〜15位 |

## 未実装・今後の課題

- [ ] 実際の写真差し替え（全プレースホルダー → WordPress経由）
- [ ] OGP画像の本番URL更新（ogp.jpgの実配置）
- [ ] lp3.html の構造化データ LocalBusiness 追加
- [ ] seo-check-lp4.html で指摘のあった missing alt属性 対応（画像差し替え時）
- [ ] Core Web Vitals 最適化（画像圧縮・遅延読み込み）
- [ ] lp5.html のインタビューセクション追加（男性スタッフ体験談）
- [ ] sitemap.xml の作成
- [ ] robots.txt の設定

## 開発メモ

### カラーパレット
- index.html: `--primary: #d45f8a`（ピンク系）
- lp2.html: `--primary: #8b3a62`（バーガンディ）
- lp3.html: `--primary: #7c3aed`（パープル）
- lp4.html: `--primary: #b4508c`（マゼンタピンク）
- lp5.html: `--primary: #1a3a5c`（ネイビー）

### フォント
- index.html: Zen Maru Gothic + Noto Sans JP
- lp2.html: Noto Sans JP + Shippori Mincho
- lp3.html〜lp5.html: Noto Sans JP + Zen Kaku Gothic New

### 注意事項
- LINE URL `https://lin.ee/XXXXXXXX` は全ページで差し替え要
- lp5.html の LINE URL は `https://lin.ee/YYYYYYYY`（男性スタッフ専用）
- 全ページ18歳以上・高校生不可の免責事項あり

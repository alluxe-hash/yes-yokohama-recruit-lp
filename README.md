# YESグループ横浜 求人LP群

## プロジェクト概要

YESグループ横浜の求人ランディングページ（LP）群です。ターゲットキーワードとユーザー属性ごとに3種類のLPを用意し、それぞれSEO最適化・構造化データ・OGP・レスポンシブ対応を実施しています。

---

## ファイル一覧・エントリーポイント

| ファイル | ターゲット | キーワード軸 |
|---|---|---|
| `index.html` | 未経験・初心者（横浜） | 横浜 初心者向風俗 未経験 求人 |
| `lp2.html` | 40代・50代・熟女・人妻 | 横浜 40代 ヘルス 求人 |
| `lp3.html` | 出稼ぎ・地方在住・短期集中 | 横浜 出稼ぎ 風俗 寮完備 |
| `lp4.html` | コンセプト・コスプレ好き | 横浜 メイド・OL・高級・ソフトヘルス 求人 |

### URL（本番）
- 公式: https://www.kyujin-yes.com/yokohama/
- LP3 canonical: https://www.kyujin-yes.com/yokohama/dekasegi/
- LP4 canonical: https://www.kyujin-yes.com/yokohama/concept/

---

## 各LP概要

### index.html（LP1：未経験・初心者向け）
- **Canonical**: https://www.kyujin-yes.com/yokohama/
- **カラー**: ピンク系（#d45f8a → 彩度を抑えた自然なトーンに変更）
- **フォント**: Noto Sans JP + Zen Maru Gothic
- **セクション**: ヒーロー・保証ストリップ・9メリット・収入シミュレーション・5ステップ・タイムライン・FAQ（8問）・インタビュー×4・3店舗紹介・フローティングCTA
- **構造化データ**: JobPosting（identifier・validThrough付）・FAQPage（8問）・LocalBusiness×3（各店舗個別URL・geo座標付）・BreadcrumbList
- **SEO改善（2026-04-21）**: FAQ onclickバグ修正・JobPosting identifier追加・LocalBusiness個別URL設定・BreadcrumbList URL整合・data-theme削除・フッター内部リンク追加
- **デザイン刷新（2026-04-21）**: AI感低減・斜めストライプヒーロー背景・グラデ下線セクションタイトル・左ボーダーメリットカード（ノートカード風）・縦長フォトフレームインタビューアバター・格子パターン画像プレースホルダー・reassure-strip暗色グラデ・ステップ番号を白抜き枠線スタイルに変更
- **文字数**: 約80,000文字

### lp2.html（LP2：40代・熟女・人妻向け）
- **Canonical**: https://www.kyujin-yes.com/yokohama/lp2/
- **カラー**: バーガンディ系（#8b3a62）
- **フォント**: Noto Sans JP + Shippori Mincho
- **セクション**: ヒーロー・選ばれる理由（円形番号バッジ＋コネクター）・リアル収入例・9メリット・FAQ・2店舗紹介・インタビュー×4（カード型写真枠付）・ギャラリー×6（交互大小グリッド）
- **構造化データ**: JobPosting（identifier付）・FAQPage（6問）・LocalBusiness×2（geo座標付）・BreadcrumbList
- **SEOスコア**: 推定81〜85点（H1キーワード・identifier・FAQバグ修正・内部リンク改善済）
- **デザイン**: 2026-04-21 デザイン刷新（画像枠囲み線全挿入・カード型インタビュー・交互大小ギャラリー・AI感低減・女性向けポップ化）
- **文字数**: 約65,000文字

### lp3.html（LP3：出稼ぎ・寮完備）
- **Canonical**: https://www.kyujin-yes.com/yokohama/dekasegi/
- **カラー**: パープル系（#9b3b8a）＋アクセントオレンジ（#e87b2e）
- **フォント**: Noto Sans JP + Zen Maru Gothic
- **ターゲット**: 地方在住・出稼ぎ希望・短期集中・18〜45歳
- **SEOスコア**: 推定88〜90点（H1/H2キーワード・identifier・内部リンク改善済）
- **文字数**: 約64,400文字

---

## LP3 詳細仕様（出稼ぎ・寮完備）

### 対象キーワード

| キーワード | 検索数 | 競合 | CTR | 優先度 |
|---|---|---|---|---|
| 横浜 出稼ぎ ファッションヘルス 寮 | 80-150 | 2 | 87% | ★★★ |
| 横浜 出稼ぎ 風俗 求人 | 150-300 | 3 | 83% | S（最大ボリューム） |
| 横浜 ヘルス 短期 出稼ぎ 求人 | 60-120 | 2 | 86% | S |
| 横浜 大手 出稼ぎ ヘルス 寮あり | 40-80 | 2 | 88% | S |
| 横浜 ヘルス 寮完備 求人 | 80-150 | 2 | 87% | S |
| 横浜 風俗 出稼ぎ 交通費支給 | 60-120 | 2 | 86% | S |
| 横浜 ファッションヘルス 1週間 出稼ぎ | 30-80 | 1 | 90% | S |
| 横浜 風俗 出稼ぎ 30万 保証 | 30-70 | 1 | 91% | S（競合最小） |

### セクション構成

1. **ヒーロー** — 7日間30万円保証・即日入寮・荷物1つでOK
2. **保証ストリップ** — 6大特典バー（保証・入寮・交通費・日払い・盗撮対策・24h相談）
3. **保証詳細** — 30万円保証Big Box＋6メリットカード
4. **寮情報** — 個室・オートロック・Wi-Fi・1泊2,500円・徒歩圏内・送迎
5. **収入シミュレーション** — 3日〜1ヶ月の期間別収入例テーブル
6. **全8店舗カード** — 各店舗URL・日給目安・ジャンル・説明付き
7. **応募フロー5ステップ** — LINE相談→店舗選択→入寮→研修→稼働
8. **インタビュー3名** — 地方出身者のリアルな声
9. **FAQ（6問）** — アコーディオン形式・FAQPage構造化データ対応
10. **最終CTA** — LINE相談・公式サイト応募・全8店舗リンク集
11. **フッター** — 全8店舗リンク・免責事項

### 8店舗リンク

| 店舗名 | URL |
|---|---|
| 泡ほたる | https://kanto.qzin.jp/awhotaru/ |
| エロいーな | https://yesgrp.com/yokohama/eroina/ |
| ほたる | https://kanto.qzin.jp/renaissance/ |
| 花椿 | https://www.kyujin-yes.com/yokohama/hot/top/ |
| 横浜プロダクション | https://kanto.qzin.jp/satindoll/?v=official |
| シャロン | https://kanto.qzin.jp/ypro/?v=official |
| グラマーグラマー | https://yesgrp.com/yokohama/glamour/ |
| バッドカンパニー | https://kanto.qzin.jp/yeskyu/?v=official |

### 構造化データ（JSON-LD）

- **JobPosting**: タイトル「横浜出稼ぎ・寮完備キャスト（18〜45歳）」・日給20,000〜100,000円・PART_TIME・2026-04-20〜2026-12-31（identifier付）
- **FAQPage**: 6問（交通費・寮環境・短期・未経験・身バレ・友人同伴）
- **BreadcrumbList**: 求人TOP → 横浜出稼ぎ・寮完備 全8店舗
- **LocalBusiness**: YESグループ横浜（geo座標付・openingHours付）

### SEOメタタグ

- `canonical`: https://www.kyujin-yes.com/yokohama/dekasegi/
- `og:image`: https://www.kyujin-yes.com/yokohama/lp3/ogp.jpg
- `geo.region`: JP-14
- `geo.position`: 35.4437;139.6380
- Twitter Card: summary_large_image
- Fontプリロード：`<link rel="preload" as="style">`

---

## 共通技術仕様

- **静的HTML単一ファイル構成**（CSS・JS inline）
- **外部依存**: Google Fonts（Noto Sans JP / Zen Maru Gothic / Shippori Mincho）のみ
- **CDN**: jsDelivr / Google Fonts
- **JavaScript**: FAQアコーディオン・スクロール300px後フローティングCTA表示
- **レスポンシブ**: CSS Grid + Flexbox、@media (max-width: 600px)
- **アクセシビリティ**: aria-label・role・tabindex・キーボード操作対応

---

### lp4.html（LP4：コンセプトヘルス 4店舗 ★NEW）
- **Canonical**: https://www.kyujin-yes.com/yokohama/concept/
- **OG image**: https://www.kyujin-yes.com/yokohama/lp4/ogp.jpg
- **テーマ**: ダークモード（--bg: #0e0820）＋マルチカラー（メイド/OL/高級/ソフト別）
- **フォント**: Noto Sans JP + Shippori Mincho
- **ターゲット**: コスプレ・コンセプト好き・18〜45歳・未経験〜経験者
- **4コンセプト**:
  - 🎀 メイド系 → グラマーグラマー（最大100,000円/日）
  - 💼 OL系 → バッドカンパニー（最大70,000円/日・採用率98%）
  - 👑 高級ドレス系 → シャロン横浜（最大105,000円/日・バック率85%）
  - 🌿 ソフト・癒し系 → エロいーな（最大80,000円/日・ペットOK）
- **セクション**: ヒーロー・コンセプト概要Strip・稼げる3理由・4コンセプト選択・9メリット・収入実績×3・シミュレーションテーブル・4店舗カード・キーワードマトリクス・寮情報・5ステップフロー・持ち物リスト・FAQ（6問）・最終CTA
- **構造化データ**: JobPosting・FAQPage（6問）・BreadcrumbList
- **特記事項**: Cloudflare Insightsスクリプト除去済み・フローティングCTA（スクロール300px後）・キーボード操作対応FAQ
- **文字数**: 約60,900文字

---

## 未実装・今後の推奨対応

- [ ] `og:image`（各LP）の実画像URLへの差し替え
- [ ] LINEリンク（`https://lin.ee/XXXXXXXX`）を実際の公式LINEアカウントURLへ差し替え
- [ ] LocalBusiness構造化データへの実電話番号追加
- [ ] WordPress/CMSへの移植（各セクションをブロック化）
- [ ] Google Search Consoleでの構造化データ検証
- [ ] Core Web Vitals測定・画像最適化（WebP変換）
- [ ] A/Bテスト（ヒーローコピー・CTA文言比較）
- [x] LP3フッターにlp4/lp2/indexへの内部リンク追加済（2026-04-21）

---

## 更新履歴

| 日付 | 内容 |
|---|---|
| 2026-04-21 | index.html SEO改善（FAQ onclickバグ修正・JobPosting identifier/validThrough・LocalBusiness個別URL・BreadcrumbList整合・内部リンク追加） |
| 2026-04-21 | lp2.html デザイン刷新（全画像枠囲みプレースホルダー挿入・カード型インタビュー・交互大小ギャラリー・セクション装飾バー・AI感低減） |
| 2026-04-21 | lp2.html SEO改善（H1キーワード・FAQバグ修正・identifier・フッター内部リンク） |
| 2026-04-21 | lp3.html SEO全項改善（H1/H2キーワード・店舗URL修正・identifier・内部リンク） |
| 2026-04-21 | lp4.html SEO全項改善（H1/H2・内部リンク・LocalBusiness・identifier） |
| 2026-04-20 | lp4.html 新規作成（コンセプトヘルス4店舗・ドリューデザインリニューアル） |
| 2026-04-20 | lp3.html 新規作成（出稼ぎ・寮完備・全8店舗） |
| 2026-04-18 | lp2.html 作成（40代・熟女・人妻向け） |
| 2026-04-06 | index.html 作成・SEO最適化完了 |

# teremo プロジェクト

テレモ（営業代行サービス）のランディングページ。

## 技術スタック
- Vite + React 19 + Tailwind CSS v4
- `npm run dev` で起動（http://localhost:5173/）
- `npm run build` / `npm run lint`

## 主要コンポーネント
- `src/components/Header.jsx` — 固定ヘッダー、ナビ（経験者の方/初めての方/ご利用の流れ/料金）
- `src/components/Hero.jsx` — ヒーロー
- `src/components/Experienced.jsx` — 経験者向けセクション
- `src/components/Newcomer.jsx` — 初めての方向けセクション
- `src/components/ComparisonTable.jsx` — 比較表（ランキング形式）
- `src/components/Pricing.jsx` — 料金
- `src/components/Footer.jsx` — フッター

## 訴求ポイント（変更時は整合性に注意）
- 月額 14万円
- 月間 4,700コール保証
- 全コール100%ログ開示
- 初期費用 0円
- 契約縛りなし

## デザインルール
- アクセントカラー: `#f55f00`（オレンジ）
- 基調: 黒＋白＋オレンジ。タイポグラフィ中心の"editorial"寄りデザイン
- 強調パターン: サブ文（小・グレー） → メイン文（大・黒＋強調語だけオレンジ）
- 装飾は控えめ。絵文字やpulse系アニメーションは避ける
- 句読点（、。）を省略して改行で区切ることが多い
- 全体文字サイズは `src/index.css` の `body { zoom: 1.12; font-size: 18px; }` で拡大済み

## Git remote
- `origin` = https://github.com/koretada0826/teremo.git（現在のghデフォルトアカウントでは403）
- `kazujp` = https://github.com/kazujp225/telomo.git（"telomo"、eなし）
- push時は `gh auth switch -u kazujp225` → `git push kazujp main`
- ユーザーに共有する正のリンクは https://github.com/kazujp225/telomo

# CHANGELOG

## 2026-09-24

### Added
- デザイン詳細モーダル内に成果物切替（ホームページ / Webアプリ / スライド）を追加（`ai-design-style-catalog.html`）
  - STEP 1 と共通の `docType` を操作し、プレビュー・プロンプト・入力欄・コピーボタン・一覧と連動
  - 成果物切替時に MIX モーダルのプレビュー（`prevA` / `prevB`）も更新されるよう修正

### Fixed
- スマホで `h1` のサブタイトル（— 30スタイル × 3成果物 × 「AI臭さ」脱却 —）が不自然に改行される問題を修正
  - `.subtitle` クラス化し、PC では `nowrap`、スマホ（760px以下）ではブロック表示に変更

### Docs
- `README.md` から「実行方法」「リポジトリ構成」セクションを削除（`e68ab2e`）

## 2026-09-23 - 初回リリース

- docs: `README.md` のデモ URL を公開 URL に更新（`f9a5ed2`）

## 2026-09-20

- docs: `README.md` を追加（`4279966`）
- 初回コミット: `ai-design-style-catalog.html` を追加（`c66ec11`）

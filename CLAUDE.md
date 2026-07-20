# CLAUDE.md — HomeAI（コード側）

このリポは HomeAI の **実装コード専用**。企画・投稿・ストーリー・営業導線は Obsidian Vault（`App Ideas/HomeAI Project/`）にあり、ここには置かない。

## このリポでやること
- `index.html` の実装（登録→検索→表示の機能）、UI、GitHub Pages 公開。
- バグ修正メモ・実装メモは簡潔に（企画メモは増やさない）。

## 反映のルール
- **企画で決まった内容だけ** を README / コードに反映する。仕様の"決定事項"のみ持ち込む。
- 迷ったら企画（Vault側）が正。ここでは実装判断に集中する。

## 技術メモ
- 単一 `index.html`（依存なし）で動かす方針。データは localStorage 想定（AKARI と同様）。
- GitHub Pages：`main` / root 公開、`.nojekyll` あり。

## 公開
- https://naomimatsui.github.io/homeai/ （Pages有効化後）

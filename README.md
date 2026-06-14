<!-- Purpose: Explain the repository structure and the Japanese-first update workflow. -->

# 生態学・植物科学のためのBase R

このリポジトリは、Quartoとquarto-live/webRで作るインタラクティブな
Base Rチュートリアルです。

## 更新方針

日本語版を正本として更新します。通常の教材追加・修正は、root直下の
`index.qmd`、`basics/`、`exercises/` を編集します。

英語版は、内容が固まったタイミングで日本語版から `en/` 以下へ同期します。
英語版を作るときも、Rコードとデータ参照は日本語版と同じにします。

## ディレクトリ

- `index.qmd`: 日本語版トップページ
- `basics/`: 基礎教材
- `exercises/`: 練習問題
- `data/`: 教材用データ
- `en/`: 将来の英語版ページ
- `_extensions/`: quarto-live拡張
- `.github/workflows/`: GitHub Pages公開用Workflow

## 英語版同期を依頼するときの文例

```text
日本語ページを正本として、英語版 en/ 以下を同期してください。
Rコードと演習内容は日本語版と同じにして、説明文だけ自然な英語にしてください。
```

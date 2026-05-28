# decks

koki 個人プロダクト・チャンネル企画・思考メモの HTML 置き場。GitHub Pages で配信。

- 公開URL: https://akira1999work-debug.github.io/decks/
- 公開設定: **public + noindex**（URL を知ってる人だけ向け。Google 検索には出ない）
- 対象: koki 個人オリジナル（mihaku / kotonoha / すまし猫流 AI開発日誌 等）
- 対象外: Eden 系（別会社所有 → `EdenLTD/eden-decks` 側に置く）

## 追加方法

1. 新しい `*.html` をリポジトリ直下に置く
2. HTML 先頭に `noindex` メタを必ず入れる:
   ```html
   <meta name="robots" content="noindex, nofollow, noarchive, nosnippet">
   <meta name="googlebot" content="noindex, nofollow, noarchive, nosnippet">
   ```
3. `index.html` のリストに新規 `<li>` を**先頭に**追加（最新が上）
4. main に push（Pages が自動デプロイ、数十秒〜数分）

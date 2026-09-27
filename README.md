# Ryotaro Kawata — Research CV

公開サイト: https://ryotaro-kawata-wa.github.io/

所属・学歴・研究経験・受賞・論文をまとめた英語・日本語の研究CVです。
外部ライブラリやビルド処理を使わず、`index.html` だけで表示できます。
英語本文は静的HTMLなので、JavaScriptを無効にしても読めます。
ページ上部の **EN / JA** で表示言語を切り替えられ、選択は同じブラウザーに保存されます。
`?lang=en` / `?lang=ja` 付きのURLで言語を指定して共有できます。

## 更新方法

1. `index.html` の該当するセクションを編集します。論文は `id="publications"` の一覧です。
2. 新しい論文は `<li class="paper">` を複製し、タイトル、全著者、採択先／年、リンクを更新します。`*` はequal contributionを意味します。
3. 日本語訳は各要素の `data-ja`、読み上げラベルは `data-ja-aria-label` を編集します。最終更新日も両言語で変更し、表示を確認します。
4. `main` に反映すると、既存のGitHub Pages設定で公開されます。Actionsの `pages build and deployment` が成功したことを確認してください。

ブラウザーの印刷機能またはページ上の **Print / Save PDF** ボタンで、印刷用のCVとして保存できます。PDF保存時はブラウザーのヘッダーとフッターをオフにすると整います。

## 論文情報

- Google Scholar: https://scholar.google.com/citations?user=MJvufWcAAAAJ&hl=en
- 各論文の会議公式ページ、OpenReview、arXiv（ページ内リンク）

会議年とarXiv公開年が異なる場合は、会議論文には会議年を使用します。引用数など頻繁に変わる指標は掲載していません。

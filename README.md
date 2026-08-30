# AIでつくる 大人の絵本づくりガイド

GitHub Pagesへそのまま公開できる静的サイトです。ビルドは不要です。

## 公開方法

1. このフォルダ内のファイルと `assets` フォルダを、GitHubリポジトリのルートへアップロードします。
2. GitHubで `Settings` → `Pages` を開きます。
3. `Build and deployment` の `Source` を `Deploy from a branch` にします。
4. 公開ブランチを `main`、フォルダを `/(root)` にして保存します。

`index.html`、`styles.css`、`script.js`、`.nojekyll`、`assets/` の階層を変えないでください。

## LINE URLの変更

`script.js` 冒頭の `LINE_URL` だけを書き換えてください。

# ポートフォリオサイト

情報系大学院生（28卒）のポートフォリオ。研究・プロダクト・スキルを掲載。

## 公開手順（GitHub Pages）

1. GitHubで新しいリポジトリを作成（例：`portfolio`）
2. このフォルダの中身（`index.html` / `style.css` / `README.md`）をpush
3. リポジトリの **Settings → Pages** を開く
4. **Source** を `Deploy from a branch` にし、Branch を `main` / フォルダ `/ (root)` に設定して Save
5. 数分後、`https://<ユーザー名>.github.io/portfolio/` で公開される

> ユーザーサイト（トップに `username.github.io` でアクセスさせたい）場合は、
> リポジトリ名を **`<ユーザー名>.github.io`** にすると `https://<ユーザー名>.github.io/` で公開できます。

## 公開前に必ず差し替える箇所

`index.html` 内のコメント `▼▼ … ▲▼` で囲んだ部分：

- [ ] **氏名**（`宇佐見 〇〇`）
- [ ] **連絡先メールアドレス**（`your-email@example.com`）
- [ ] **GitHubリンク**（`https://github.com/your-account`）

## ローカルでの確認方法

`index.html` をブラウザで開くだけでOK（ビルド不要の静的サイト）。

## 注意（記載内容のルール）

- 学会発表は「査読付き論文」とは書かない（「研究発表」「学会発表」と表記）
- ブレイクゲートは「先行研究をもとに開発」と正確に記載

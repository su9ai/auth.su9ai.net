# auth.su9ai.net

Google Auth Platform（OAuth 同意画面）の本番審査に必要な **アプリケーションのホームページ**、**プライバシーポリシー**、**利用規約** を公開するための GitHub Pages リポジトリです。

このサイトは Jekyll で構築されています。

## 公開サイト

<https://auth.su9ai.net/>

## 主なページ

| ページ | URL |
|---|---|
| ホームページ | `/` |
| プライバシーポリシー | `/privacy-policy/` |
| 利用規約 | `/terms-of-service/` |
| お問い合わせ | `/contact/` |

## ローカルでの確認

Ruby/Bundler が入っている場合：

```bash
bundle install
bundle exec jekyll serve
```

Ruby が入っていない場合は Docker でビルドできます：

```bash
docker run --rm -v "$PWD":/srv/jekyll jekyll/jekyll:4.2.0 jekyll serve
```

## カスタマイズが必要な箇所

`_config.yml` と各 Markdown ファイル内のプレースホルダーを、実際のアプリ・運営者情報に置き換えてください。

- `_config.yml`：サイト名・説明・運営者名・問い合わせメールアドレス
- `index.md`：サービスの具体的な概要
- `privacy-policy.md`：取得するデータ・保存期間など
- `terms-of-service.md`：準拠法・管轄など

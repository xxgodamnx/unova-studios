# UNOVA STUDIOS — Official Website

UNOVA STUDIOSの公式ホームページ。モバイル対応の静的Webサイトです。

## サイト構成

- `index.html` — HTML・CSS・JavaScriptをまとめたWebサイト本体
- `favicon.svg` — ブラウザタブ用のUロゴ
- `social-card.svg` — シェア時のプレビュー画像用素材

## GitHub Pagesで無料公開する

1. [Settings → Pages](https://github.com/xxgodamnx/unova-studios/settings/pages) を開きます。
2. **Build and deployment → Source** を **Deploy from a branch** に変更します。
3. **Branch** を `main`、**Folder** を `/(root)` にして **Save** を押します。
4. 数分後、サイトが https://xxgodamnx.github.io/unova-studios/ で公開されます。

## 連絡先

- `unovastudiosjp@gmail.com` （mailtoリンク）
- メール送信は閲覧者のメールアプリで行うため、サーバー側の送信処理はありません。

## 留意点

- サービス内容は構想段階の紹介文です。実績、所在地、料金などは未掲載です。
- 公開するとページとメールアドレスを誰でも閲覧できます。
- ブランド名・ロゴの権利や商標のクリアランスは未確認です。
- テキストやデザインは `index.html` から編集できます。

## SEO / Google Search Console

このリポジトリには以下の基礎的なSEO設定が含まれています。

- `index.html`: 検索結果タイトル、説明文、canonical、OG情報、JSON-LD構造化データ、読み上げ用ブランド名
- `sitemap.xml`: 検索エンジン向けのURL一覧

### Googleの検索結果に登録をリクエストする

1. [Google Search Console](https://search.google.com/search-console/) にログインする。
2. URLプレフィックスとして `https://xxgodamnx.github.io/unova-studios/` を登録する。
3. 提示されるHTMLタグまたはHTMLファイルで所有権を確認する（必要ならGitHubのファイルを編集・追加する）。
4. 「サイトマップ」に `https://xxgodamnx.github.io/unova-studios/sitemap.xml` を送信する。
5. 「URL検査」でトップページのインデックス登録をリクエストする。

Googleによるインデックス登録や検索順位1位は保証されません。事例や提供サービスの情報を充実させ、公式SNSからホームページへリンクすることも重要です。

### 独自ドメインに切り替える場合

`unovastudios.com` 等を取得してGitHub Pagesへ接続した後、**index.html の canonical、OG URL、構造化データ内のURLと sitemap.xml を新ドメインへ変更**してからSearch Consoleも新URLで設定してください。現状ではGitHub Pages URLが正規URLです。

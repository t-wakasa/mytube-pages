# MyTube Pages

公開URL: https://t-wakasa.github.io/mytube-pages/

アプリの元コード・テスト・動画生成スクリプトはPrivateリポジトリに保持します。
このPublicリポジトリには配信用ワークフローだけを置き、Pagesへアップロードするのはビルド済みの `dist/` のみです。
既存の読み取り用シークレット `MYTUBE_READ_TOKEN` を使います。値は公開しません。

今回のリリースは検証済みのソースコミット `62013ff7eb25e9e859f2c97f94455b9c8118e7a3` に固定しています。
`release/rich-site` ブランチへのpushで改善版を公開し、masterへの直接pushや強制pushは行いません。
このワークフローをmasterへ残す場合はPull Requestをレビューしてマージできます。

公開されるJavaScript・CSS・画像・動画は、通常のWebサイトと同様に閲覧者が取得できます。
ソースマップ・元のTypeScript・テスト・生成スクリプトは配信しません。

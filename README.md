# MyTube Pages

公開URL: https://t-wakasa.github.io/mytube-pages/

アプリの元コード・テスト・動画生成スクリプトはPrivateリポジトリに保持します。
このPublicリポジトリの `site/` には、検証済みのビルド成果物（HTML・圧縮済みJS/CSS・SVG・MP4）のみを置きます。

Season 02: 特集ヒーロー・並べ替え・表示切り替え・再生速度・シアターモード・音声付きアニメーション12本。
ソースコミット: `62013ff7eb25e9e859f2c97f94455b9c8118e7a3`。
ソース側で型チェック・全14テスト・動画生成と音声/動き/全編デコード検証・ビルドを実施しました。
配信物のハッシュを `site/release.json` で確認できます。

Actionsは配信物の整合性を確認し、`site/` だけをGitHub Pagesへ公開します。
Privateソースの読み取りトークンは不要です。既定のGITHUB_TOKENだけを使用します。
`release/rich-site` とmasterへのpushが公開対象です。masterへの直接pushや強制pushは行いません。
ワークフローをmasterへ残す場合はPull Requestをレビューしてマージできます。

公開されたJS・CSS・画像・動画は、通常のWebサイトと同様に閲覧者が取得できます。
元のTypeScript・テスト・生成スクリプト・ソースマップは配信しません。

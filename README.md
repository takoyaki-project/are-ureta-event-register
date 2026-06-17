# あれ売れた？ PWA v1.6

GitHub Pages 公開用ファイルです。

## アップロードするファイル

- index.html
- manifest.json
- sw.js
- icon-192.png
- icon-512.png

この5つを同じ階層に置いてください。

## GitHub Pages で使う手順

1. 新しいリポジトリを作る、または既存リポジトリに入れる
2. 上記5ファイルをアップロード
3. Settings → Pages
4. Branch を `main`、フォルダを `/root` にして保存
5. 表示されたURLをスマホ・タブレットで開く
6. Safari / Chrome の共有メニューから「ホーム画面に追加」
7. 一度オンラインで開いておくと、以後オフラインでも起動しやすくなります

## 注意

- 販売データは端末のブラウザ内に保存されます。
- 別端末とは自動同期されません。
- Service Worker は `https://` または `localhost` で動きます。GitHub Pages は対応しています。

# あれ売れた？ PWA v1.12

売ったあと、記録で困らないイベント販売レジ。  
バザー・夏祭り・文化祭などで、売上・在庫・完売時間を記録できます。

## 公開URL

https://takoyaki-project.github.io/are-ureta-event-register/

## v1.12 の変更点

- 商品登録に「グループ」と「カテゴリ」を追加
- 販売画面ではグループ名を表示しない
- 結果画面と引継ぎレポートでグループ別小計を表示
- 商品マスタを `localStorage` に保存
- 次回以降、「前回の商品を使う」から商品を呼び出し、今回の在庫数だけ入力できるように変更
- 「イベントを始める」の次に「商品を準備する」画面を追加
- 商品一覧を編集する画面を追加
- 入力ステップ下部に戻るボタンを追加し、スマホ操作を改善
- PWAキャッシュ名を v1.12 に更新
- `manifest.json` の `start_url` を `index.html?v=1.12` に更新

## v1.11 から継続している対策

- トップ画面はA案ベース
- トップ専用の `top-menu-grid` を1個だけ配置
- 旧 `devnav` は画面上に表示しない
- `.devnav` が万一残ってもCSSで非表示
- PWA / GitHub Pages 対応

## GitHub Pages に置くファイル

- index.html
- manifest.json
- sw.js
- icon-192.png
- icon-512.png

## ブランチ作業メモ

推奨ブランチ名：

```bash
feature/group-summary-product-master
```

mainブランチとは分けて作業し、動作確認後にマージします。

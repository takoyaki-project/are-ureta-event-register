# あれ売れた？ PWA v1.11

トップ画面の10個メニュー重複対策をさらに強化した版です。

## v1.11 の変更点

- 旧 `devnav` メニューを全削除
- トップ専用の `top-menu-grid` を1個だけ配置
- `.devnav` が万一残ってもCSSで非表示
- PWAキャッシュ名を v1.11 に更新
- `manifest.json` の `start_url` を `index.html?v=1.11` に更新

## 生成時チェック

- devnav count: 0
- top-menu-grid count: 1
- devnav in s1: 0
- top-menu-grid in s1: 1

## GitHub Pages に置くファイル

- index.html
- manifest.json
- sw.js
- icon-192.png
- icon-512.png

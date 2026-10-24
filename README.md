# FORTNITE 精霊チェックリスト

スマートフォン・タブレット・PCで使える、Fortniteの精霊コレクション用チェックリストです。濃紺のUI、シーズン切り替え、取得・マスター状態、進捗表示、画像保存、バックアップコードに対応しています。

## 使い方
1. ページを開き、ボード上の精霊のチェック欄をタップ／クリックします。
2. 1回目で取得済み、2回目でマスター、3回目で未取得に戻ります。
3. 進捗は利用中のブラウザーの `localStorage` に保存されます。別端末へ移動する場合は「精霊コード」でバックアップしてください。
4. 「画像保存」で現在のチェック状態をPNGに出力できます。「画像コピー」は対応ブラウザーのみ利用できます。
5. 「全チェック削除」は確認ダイアログの後に現在のシーズンの状態を消去します。

## 公開方法（GitHub Pages）
1. GitHubでこのリポジトリを開きます。
2. **Settings → Pages** を開きます。
3. **Build and deployment → Source** を **GitHub Actions** に設定します。
4. `.github/workflows/pages.yml` が実行された後、表示されたPages URLを開きます。

## ファイル
- `index.html` — UIとクライアント側の機能
- `data/layout-geometry.v12.json` — ボードのクリック位置データ
- `data/identity.v12.json` — シーズン4の精霊表示データ

## 素材と帰属表示
このリポジトリのUIコードは独自に作成しています。ボードのキャラクター画像とレイアウト参照データは、参考プロジェクト [SC-BCH/fortnite-sprite-checklist](https://github.com/SC-BCH/fortnite-sprite-checklist) にある素材を参照しています。画像は現在、同プロジェクトの公開Raw URLから読み込むため、素材URLやアクセス条件が変わると表示に影響します。画像素材の利用条件は元の権利者と参考プロジェクトの条件に従ってください。

Fortniteおよび関連するキャラクター・アートは各権利者に帰属します。本サイトは非公式のファン制作物であり、Epic Gamesとの提携・承認を受けていません。

## プライバシー
このサイトはチェック状態をブラウザー内に保存し、独自のサーバーへ送信しません。バックアップコードを他人に渡すと、コードに含まれる表示名とチェック状態も共有されます。

## License
独自に作成したHTML/CSS/JavaScript部分はMIT Licenseとします。参考プロジェクト由来のデータや画像素材、Fortniteの商標・キャラクター素材にはこのライセンスは適用されません。素材の利用前に各権利者の条件を確認してください。

MIT License

Copyright (c) 2026 fortnite-sprite-checklist contributors

Permission is hereby granted, free of charge, to any person obtaining a copy of the software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.

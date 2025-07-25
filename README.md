# アメダス最高気温検索

日本全国のアメダス観測所の当日最高気温を検索できるWebアプリケーションです。

## 🌐 デモ

GitHub Pagesで公開中: [https://[あなたのユーザー名].github.io/[リポジトリ名]/](https://[あなたのユーザー名].github.io/[リポジトリ名]/)

## 🚀 機能

- 地点名を入力して最高気温を検索
- 全国のアメダス観測所に対応
- レスポンシブデザイン
- よく検索される地点のクイックアクセス

## 📱 使い方

1. 地点名（例：東京、大阪、札幌）を入力
2. 「検索」ボタンをクリック
3. 最高気温と観測時刻が表示されます

## 🛠️ 技術仕様

- HTML/CSS/JavaScript（バニラJS）
- Yahoo!天気からデータを取得
- GitHub Pagesでホスティング
- CORS制限回避のためプロキシサービスを使用

## 📊 データソース

- 気象データ: Yahoo!天気
- 観測所情報: 気象庁アメダス

## 🔧 ローカル開発

```bash
# リポジトリをクローン
git clone https://github.com/[あなたのユーザー名]/[リポジトリ名].git

# ディレクトリに移動
cd [リポジトリ名]

# ローカルサーバーを起動（例：Python）
python -m http.server 8000

# ブラウザでアクセス
# http://localhost:8000
```

## 📝 ライセンス

MIT License

## 🤝 コントリビューション

プルリクエストやイシューの報告を歓迎します！

## ⚠️ 注意事項

- このアプリケーションはYahoo!天気のデータを使用しています
- データの取得にはプロキシサービスを使用しているため、レスポンス時間が遅い場合があります
- 商用利用の場合は、適切なAPIの使用を検討してください
# Backgammon Position Maker

XGIDから同一寸法（702×546）の盤面図と、編集可能な解析図を作成する静的Webアプリです。

## 主な機能

- 複数XGIDの一括入力
- 盤面PNG・解析PNGの個別出力
- 全画像のZIP一括出力
- チェッカープレイ候補の青反転（未選択も可）
- 解析候補・エクイティ・エラー・確率表示の編集
- 全入力内容のJSON保存／復元

ブラウザで `index.html` を配信すれば動作します。外部依存はありません。

盤面デザインと描画仕様は `yanagibackgammon/position-drill` を参照しています。

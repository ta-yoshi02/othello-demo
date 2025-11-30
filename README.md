## Othello AI (Scala.js)

Scala 3 / Scala.js で書いた Othello / Reversi AI のビルド成果物だけを公開するためのリポジトリです。`public` ディレクトリをそのまま配布・ホスティングすればブラウザで遊べます。

### 構成

```
public/
  index.html   # GUI と Scala.js で描画した盤面
  styles.css   # 公開向けのテーマ・レイアウト
  main.js      # Scala.js のビルド成果物（非公開ソースから生成）
```

### ローカルで遊ぶ

1. リポジトリを取得後、`public` ディレクトリをルートに簡易サーバーを立てます。
   - 例: `python3 -m http.server 4321 --bind 127.0.0.1 -d public`
2. ブラウザで `http://127.0.0.1:4321/` を開き、先手/後手のプレイヤー種別を選んで開始してください。
   - Human / Minimax / AlphaBeta / Asterion(win) / Nemesis(lose) を選択可能です。

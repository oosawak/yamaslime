# 山スライム / Yama Slime

Three.js + Tauri で作った、スライムを積み上げるテトリス風ゲームです。

## ルール

- スライムは3ブロックまたは5ブロックの形で上から落ちてきます。
- 落下中・積み上がったスライムをクリックすると砂になります。
- 砂になったブロックで横一列が埋まると、その列が消えます。

## 起動

```bash
npm install
npm run tauri dev
```

ブラウザで試す場合は `python3 -m http.server 8000 --directory src` を実行し、`http://localhost:8000` を開いてください。

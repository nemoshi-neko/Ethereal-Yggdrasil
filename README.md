# 🌳 カラフル・ツリー 🎨

みんなー！　こんにちはー！  
とってもステキな木を植えてみました！

## プレビュー

![Image](https://github.com/user-attachments/assets/b5658c00-0da4-4a14-823e-e77ae06fdfda)  
*   [見てみる](https://nemoshi-neko.github.io/Colorful-Tree/) - 創造的なコーディングのためのJavaScriptライブラリ

## 🌸 機能

*   **カラフルな実:** 木には、パステルカラーの可愛い実がなります。マウスを乗せると、ぷっくり膨らみます。
*   **はじけるパーティクル:** 実をクリックすると、キラキラしたパーティクルが弾けてとってもきれい！
*   **流れる雲と空:** 背景は、上から下へ空色のグラデーション。白い雲がゆっくり流れて癒やされます。
*   **またたく星:** 木の枝には、キラキラとまたたく小さな星が生まれます。
*   **インタラクティブな枝:** マウスを上下に動かすと、木の幹の太さが変わります。

## 🚀 はじめ方

とってもかんたん！

1.  このリポジトリをダウンロードします。
2.  `index.html` ファイルを、お好きなブラウザで開きます。

これだけで、あなただけのカラフル・ツリーが目の前に現れます！

## 🔧 カスタマイズ

`Yggdrasil.js` ファイルのいちばん上にある `CONFIG` の数字を変えることで、簡単に自分好みの木に調整できます。

```javascript
const CONFIG = {
    FRUIT_COUNT: 50,      // 木になる実の最大数
    STAR_COUNT: 30,       // 表示される星の最大数
    CLOUD_COUNT: 5,       // 画面内に表示される雲の数

    MAX_DEPTH: 8,         // 木の枝が分岐する最大の深さ
    TRUNK_LENGTH_RATIO: 0.2, // 幹の長さ (画面の高さに対する割合)

    STAR_MIN_SIZE: 2,       // 星の最小サイズ
    STAR_MAX_SIZE: 5,       // 星の最大サイズ
    STAR_TWINKLE_SPEED: 4,  // 星のまたたきの速さ
};
```

## 🛠️ 使用技術

*   [p5.js](https://p5js.org/) - 創造的なコーディングのためのJavaScriptライブラリ

---

このプロジェクトを楽しんでくれたら嬉しいです！ 💖

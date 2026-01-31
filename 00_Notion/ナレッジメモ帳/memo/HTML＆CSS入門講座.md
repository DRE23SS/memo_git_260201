---
タグ:
  - 天職・リスキリング
作成日: Invalid date
最終更新日時: Invalid date
---

![[スクリーンショット_2025-01-25_160718.png]]

- サイトマップの作成

  [https://cacoo.com/app/o/E1Mx1sezOS/recent](https://cacoo.com/app/o/E1Mx1sezOS/recent)

  2 層以内に収める

- ファイル階層

  project

  index.html

  📁CSS

  .css

  📁images

- web 上に公開

  サーバの準備

  ロリポップ！レンタルサーバー

  さくらインターネット

- ドメイン取得

  お名前.com

  ムームードメイン

- ファイルのルール

  ファイル名はすべて小文字で表記する

  ホームページは index.html

- 読みやすい文字数・行数

  文章一段落で 3~5 行

  30~45 文字

- 適切な文字サイズ

  14px~18px

  サイズのバリエーションは 2~5 種類

  行間の設定 1.5~1.9

- 文字のジャンプ率

  見出しと本文の文字サイズの比率

  ジャンプ率が高い＝躍動や楽しい

  ジャンプ率が低い＝上品や落ち着き

- web フォント

  [https://fonts.google.com/selection/embed](https://fonts.google.com/selection/embed)

  ```CSS
  .zen-maru-gothic-regular {
    font-family: "Zen Maru Gothic", serif;
    font-weight: 400;
    font-style: normal;
  }
  ```

  ```HTML
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Potta+One&family=Yuji+Mai&family=Zen+Maru+Gothic&display=swap" rel="stylesheet">
  ```

- web 上の単位

  - 相対単位

    - ％　親要素を基準とした時の割合の単位

    - em 親要素を基準にした単位

      - 親要素が 16px のとき 16px=1em

    - rem ルート要素 html タグのサイズを基準に計算

      - html 要素が 16px のとき 16px=1rem

    - vw ビューポート(サイトの表示領域)を基準にする

      - 幅が 1200 の px 時　 50vw は 600px

      - 表示領域の幅によって変動する

    - vh ビューポートの高さを基準とした割合
      - 高さが 800px のとき　 50vh は 400px

  - 絶対単位
  - px 他要素の影響を受けない　柔軟性がない

#HTML #CSS #Web 制作 #フロントエンド

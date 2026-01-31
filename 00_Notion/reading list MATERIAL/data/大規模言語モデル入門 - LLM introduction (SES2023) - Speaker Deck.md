---
リンク: https://speakerdeck.com/kyoun/llm-introduction-ses2023
評価: ⭐️⭐️⭐️⭐️
ステータス: 読了
種別: LLM
読了日: Invalid date
電話: Invalid date
---
[6 Copyright 2023 NTT CORPORATION ニューラルネットワークの学習のイメージ タスク:テキストを2つのクラスに分類 2次元ベクトルを出力 正解クラスの 値を大きく 不正解クラス の値を小さく “メロスは激怒した。” 感情判定 モデル “negative” “positive” タスク:入力に続く次の単語を生成 語彙サイズの次元数のベクトルを出力 “メロスは” 言語モデル “激怒” 正解単語の値を 大きく “走る” 他の値を 小さく • 自然言語処理タスクの多くは「分類問題」として，ニューラルネットの出力を正解に近づけるように学習を行う](https://files.speakerdeck.com/presentations/1e9755ac257c49139f279c34b33afd11/slide_5.jpg?26869022)

[![](https://files.speakerdeck.com/presentations/1e9755ac257c49139f279c34b33afd11/preview_slide_5.jpg?26869022)](https://files.speakerdeck.com/presentations/1e9755ac257c49139f279c34b33afd11/preview_slide_5.jpg?26869022)

[7 Copyright 2023 NTT CORPORATION 初期のニューラル自然言語処理 タスク特化 ニューラル ネット構造 できれば 数万件程度欲しい タスク応用 モデル タスクデータで学習 • タスク毎に適したニューラルネットワークを設計し，正解情報付きのデータセットで学習していた • 深層学習により性能は高まったが，学習データが少ないと高い精度は実現しにくい課題が残っていた](https://files.speakerdeck.com/presentations/1e9755ac257c49139f279c34b33afd11/slide_6.jpg?26869023)

[![](https://files.speakerdeck.com/presentations/1e9755ac257c49139f279c34b33afd11/preview_slide_6.jpg?26869023)](https://files.speakerdeck.com/presentations/1e9755ac257c49139f279c34b33afd11/preview_slide_6.jpg?26869023)

[8 Copyright 2023 NTT CORPORATION 言語モデルの「事前学習」が主流に 事前学習済 言語モデル タスク応用 モデル 汎用 ニューラル ネット構造 大規模コーパスで 事前学習 ファイン チューニング アノテーションなし テキストコーパス • 言語モデル（Language Model; LM）は，単語（トークン）列の生成尤度をモデル化し、将来の（あるいは 欠落した）トークンの確率を予測する • 2018年頃から，言語モデルが自然言語処理の「基盤」として有効であると注目を集めるようになり，タスクは大き く2種類に集約されていった 正解情報ありの 学習データ](https://files.speakerdeck.com/presentations/1e9755ac257c49139f279c34b33afd11/slide_7.jpg?26869024)

[![](https://files.speakerdeck.com/presentations/1e9755ac257c49139f279c34b33afd11/preview_slide_7.jpg?26869024)](https://files.speakerdeck.com/presentations/1e9755ac257c49139f279c34b33afd11/preview_slide_7.jpg?26869024)
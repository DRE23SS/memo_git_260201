# Midjourneyでロゴを生成するプロンプトテクニック

> [!abstract] 記事の概要
> Midjourneyを使ってプロ品質のロゴを作成するためのプロンプト構成術と、具体的なキーワード集。
> 出典：[WEEL | Midjourneyで弊社の「新ロゴ」を生成してみた！プロンプトテクニック](https://weel.co.jp/media/tech/midjourney-logo/)

---

## 🏗️ ロゴ作成の基本プロンプト構成

プロンプトは以下の順序で構成すると精度が高まります。

1.  **メインテーマ**（何のロゴか？）
2.  **スタイル**（ミニマル、グラデーションなど）
3.  **背景**（白背景が加工しやすい）
4.  **除外要素**（テキストなど不要なもの）

> [!example] 基本構文
> **Logo design for [テーマ], [スタイルキーワード], white background --no text realistic photo details**

---

## 🎨 プロンプトの4つのアプローチ

記事では、指示の出し方を4つのパターンに分類しています。

### 1. 説明系（見た目を指定）
具体的な色・形・雰囲気を言語化する方法。
> [!tip] キーワード例
> `Simple`, `Minimal`, `Line art`, `Geometric`, `Blue and White`

### 2. 概念系（想いを指定）
ロゴで伝えたい抽象的なイメージや価値観を指定する方法。
> [!tip] キーワード例
> `Trust` (信頼), `Authority` (権威), `Innovation` (革新), `Friendly` (親しみやすさ), `Speed` (スピード感)

### 3. 機能系（ビジネス内容を指定）
事業内容やターゲット層を説明する方法。
> [!tip] キーワード例
> `Tech startup`, `Coffee shop`, `Fitness app`, `Organic food`, `Luxury brand`

### 4. 固有名詞系（スタイルを模倣）
既存の有名ロゴやデザイナーの名前を借りる方法（※著作権に配慮が必要）。
> [!tip] キーワード例
> `Apple style`, `Nike style`, `Paul Rand` (著名デザイナー), `Rob Janoff`

---

## 🗝️ 実践！スタイル別プロンプト集

### シンプル・ミニマル（汎用性高）
> [!note] Prompt
> **Flat vector logo of [モチーフ], minimal, simple, clean lines, white background --no text**

### グラデーション・テック系（IT企業向け）
> [!note] Prompt
> **Logo design for a tech company, abstract shape, gradient blue and purple, modern, futuristic, white background --no text**

### マスコット・キャラクター系
> [!note] Prompt
> **Mascot logo of [動物など], vector art, esports style, bold lines, vibrant colors, white background --no text**

### 幾何学的・抽象系
> [!note] Prompt
> **Abstract geometric logo, golden ratio, symmetry, shapes, modern art style, white background --no text**

---

## ⚙️ 必須パラメータとコツ

* **`--no text`**: Midjourneyは文字入れが苦手なため、最初から「文字なし」を指定してアイコン部分の作成に集中させるのが定石。
* **`--no realistic photo details`**: 写真のようなリアルさを排除し、イラスト・ロゴっぽさを強める。
* **白背景指定 (`white background`)**: 生成後の切り抜き（透過処理）を容易にするために必須。

> [!check] 活用ステップ
> 1. Midjourneyでシンボルマークを作成
> 2. IllustratorやCanvaなどの外部ツールで文字（社名）を組み合わせる
> 3. ベクター化ツール（Vectorizer.AIなど）でSVGに変換する
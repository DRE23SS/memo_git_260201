## 概要
AIを活用して高品質なWebデザインやコードを出力するためのプロンプト技術のまとめ。画像生成AI（Midjourney/DALL-E 3）とテキスト生成AI（ChatGPT/Claude）の両方のアプローチをカバー。

## 1. デザインコンセプト定義のプロンプト
AIにデザイナーとしての役割を与え、前提条件を明確にする。

### 役割の定義 (Role Prompting)

あなたは世界的に有名なUI/UXデザイナーです。
以下の要件に基づいて、モダンで使いやすいWebサイトのデザインコンセプトを提案してください。

### 5W1Hの明確化

- **Who (ターゲット):** 20代〜30代のテック系ビジネスマン
    
- **What (何を作るか):** SaaSプロダクトのLP（ランディングページ）
    
- **Why (目的):** 無料トライアルの登録数を増やす
    
- **Tone & Manner:** ミニマル、信頼感、先進的、ダークモード
    

## 2. 画像生成AI用プロンプト (Midjourney / DALL-E 3)

ビジュアルイメージを作成する際のキーワード構成。

### 基本構文

> `[Subject] + [Style/Aesthetic] + [Composition] + [Color Palette] + [Parameters]`

### 有効なキーワード集

|**カテゴリ**|**キーワード例**|
|---|---|
|**スタイル**|Minimalist, Neumorphism, Glassmorphism, Brutalism, Flat Design, Material Design|
|**レイアウト**|Hero Section, Dashboard UI, Mobile App Interface, Landing Page, Grid System|
|**品質・詳細**|High Fidelity, 4k, UI/UX Design, Trending on Dribbble, Behance, Figma|
|**色・雰囲気**|Pastel colors, Gradient, Dark mode, Corporate blue, Vibrant|

### プロンプト例

Plaintext

```
High fidelity UI design of a fitness app dashboard, mobile interface, dark mode with neon green accents, minimalist charts and graphs, clean typography, rounded corners, trending on Dribbble, Figma style --ar 9:16
```

## 3. コード生成用プロンプト (ChatGPT / Claude)

デザインを実装コードに落とし込む際の指示。

### 実装指示のテンプレート

Plaintext

```
以下のデザイン要件に基づいて、[HTML/CSS/JS]のコードを作成してください。

# 要件
- フレームワーク: [React / Vue / Next.js]
- スタイリング: [Tailwind CSS / Styled Components]
- レスポンシブ対応: モバイルファースト
- デザイン: [具体的な色コードやレイアウトの指示]

# 出力形式
- コンポーネントごとにファイルを分ける
- コードブロックのみを出力
```

### 修正・改善のテクニック (Iterative Refinement)

- 「ボタンの余白をもっと広げて」
    
- 「アクセシビリティ（コントラスト比）を考慮した配色に修正して」
    
- 「Tailwindのクラスを使ってリファクタリングして」
    

## 4. UIコンポーネント別プロンプトのコツ

### ヒーローセクション

- **要素:** キャッチコピー、CTAボタン、メインビジュアル
    
- **指示:** 「コンバージョン率（CVR）を意識した配置にして」
    

### ナビゲーション

- **要素:** ハンバーガーメニュー、スティッキーヘッダー
    
- **指示:** 「UXを考慮し、スクロール時は背景をぼかす（backdrop-filter）処理を入れて」
    

### フォーム

- **要素:** 入力フィールド、バリデーション
    
- **指示:** 「ユーザーの入力負荷を下げるためのマイクロインタラクションを含めて」
    

---


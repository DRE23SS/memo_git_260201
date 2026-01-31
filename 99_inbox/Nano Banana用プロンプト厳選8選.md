[【無料配布】Nano Banana用プロンプト厳選8選！コピペで即試せる画像生成＆編集テクニック \| WEEL](https://weel.co.jp/media/innovator/nano-banana-prompts/)

## Nano Bananaのプロンプトのコツ

**Nano Banana用のプロンプトを作成する際のコツは、以下の35点。**基本的には、他の画像生成AIや[LLM](https://weel.co.jp/media/llm)同様、「具体的かつシンプルな構造のプロンプト」が推奨されます。

**Nano Bananaのプロンプトのコツ**

- プロンプトの基本要素を抑える（誰・どこで・何を・どんなテイストで）
- 構図・光・スタイル・アスペクト比を指定する
- ネガティブプロンプトで失敗を防ぐ

なお、プロンプトは自力で設計するほか、**GeminiやChatGPTと壁打ちしながら作るのもOK**です。

ここでは、Nano Bananaで安定した結果を得るためのプロンプト設計の基本的な考え方と、実践的なコツを3つのポイントに分けて解説します。

### 
プロンプトの基本要素を抑える（誰・どこで・何を・どんなテイストで）

まず押さえておきたいのが、**プロンプトに含める情報の粒度を揃えること**です。最低限、以下の4点を意識すると、生成結果が安定しやすくなります。

|要素|含める情報|
|---|---|
|誰（What / Who）|人物・モチーフ・被写体|
|どこで（Where）|背景・場所・シーン|
|何をしているか（Action / Purpose）|ポーズ・用途・状況|
|どんなテイストで（Style / Mood）|画風・雰囲気・質感|

プロンプトの基本要素一覧

例えば「猫のイラスト」とだけ書くよりも、以下のように、被写体・背景・雰囲気をセットで指定すると、意図に近い画像になりやすくなります。

```plain
A cute orange cat sitting on a sofa in a cozy living room, soft lighting, illustration style
```

### 構図・光・スタイル・アスペクト比を指定する

次に重要なのが、**画像全体の見た目を左右する要素を明示すること**です。特に以下の指定は、仕上がりに大きく影響します。

|項目|プロンプト例|
|---|---|
|構図|close-up / full body / wide shot / isometric|
|光|soft lighting / dramatic lighting / natural light|
|スタイル|anime style / realistic / watercolor / flat design|
|アスペクト比|1:1、4:5、16:9|

画像全体の見た目を左右する要素一覧

プレゼン資料向けの画像であれば、以下のように、「資料向けであること」と「横長構図」を明確にすると使いやすくなります。

```plain
isometric illustration, clean design, flat colors, 16:9
```

### ネガティブプロンプトで失敗を防ぐ

ネガティブプロンプトとは、「生成してほしくない要素」をあらかじめ指定することで、失敗を防ぐための手法です。

例えば人物画像では、以下の指定を入れることで、指や顔が不自然になるリスクを下げられます。

- extra fingers
- distorted hands
- unnatural face

ネガティブプロンプトは、プロンプトの後半にまとめて書くのが一般的で、以下のように付け加えるだけでも、安定感が大きく変わります。

```plain
…, clean illustration style, no extra fingers, no text in background
```


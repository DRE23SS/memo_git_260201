
[[Swimwear Prompt Library]]
## 概要

- 対象モデル：**Nano Banana Pro / Gemini 3 Pro Image**
- ジャンル：**実写系セルフィー・カンディッド・ミラーセルフィー**
- 方針：
  - 写真として自然
  - 非イラスト感
  - SNS / グラビア / フェチ文脈に適応可能
- 構造：**JSON構造化プロンプト（差し替え・量産向き）**

---
# 【保存版】Stable Diffusionプロンプト（呪文）リストと入力のコツ

**元記事**: [WEEL](https://weel.co.jp/media/stable-diffusion-spell/)

## プロンプト入力の基本ルール

- **言語**: 英語で入力する（精度が高い）
    
- **区切り**: カンマ（`,` ）で区切る
    
- **優先順位**: 文頭に近い単語ほど優先される
    
- **強調**: `(word)` のように括弧で囲むと強調される
    
- **ネガティブプロンプト**: 生成してほしくない要素（崩れた指、低画質など）を指定する
    

---

## 1. 人物に関するプロンプト (Person)

### 人種 (Race)

|**プロンプト**|**内容**|
|---|---|
|`japanese`|日本人|
|`american`|アメリカ人|
|`asian`|アジア人|
|`korean`|韓国人|
|`chinese`|中国人|
|`elf`|エルフ|
|`angel`|天使|
|`devil`|悪魔|

### 性別 (Gender)

|**プロンプト**|**内容**|
|---|---|
|`man`|男性|
|`woman`|女性|
|`girl`, `female child`|女の子|
|`boy`, `male child`|男の子|
|`lady`|貴婦人|
|`gentleman`|紳士|
|`bishounen`|イケメン（美少年）|

### 年齢 (Age)

|**プロンプト**|**内容**|
|---|---|
|`baby`, `infant`|乳児・赤ちゃん|
|`child`|子供|
|`young adult`|10代後半〜20代前半|
|`college age`|大学生くらい|
|`thirties`|30代|
|`middle age`|中年（40〜60代）|
|`old`, `elder`|老人|
|`10 years old`|（数字で指定）10歳|

### 肌の色 (Skin)

|**プロンプト**|**内容**|
|---|---|
|`pale skin`|色白|
|`fair skin`|明るめの肌色|
|`light brown skin`|明るい茶色|
|`tanned skin`|日焼けした肌|
|`dark skin`|ダーク系の肌|
|`ebony skin`|漆黒に近い肌|
|`olive skin`|オリーブ色の肌|
|`freckled skin`|そばかすのある肌|
|`smooth skin`|滑らかな肌|
|`glowing skin`|輝くような美肌|

---

## 2. 髪型に関するプロンプト (Hairstyle)

### 髪型・男性 (Men's Hair)

|**プロンプト**|**内容**|
|---|---|
|`short hair`|短髪|
|`buzz cut`|丸刈り・坊主|
|`undercut`|刈り上げ（ツーブロック）|
|`pompadour`|ポンパドール（七三系）|
|`messy hair`|無造作ヘア|
|`side part`|横分け|
|`man bun`|お団子（後ろ結び）|

### 髪型・女性 (Women's Hair)

|**プロンプト**|**内容**|
|---|---|
|`straight hair`|ストレートヘア|
|`bob`|ボブカット|
|`short bob`|ショートボブ|
|`long hair`|ロングヘア|
|`wavy hair`|ウェーブヘア|
|`curly hair`|カールヘア|
|`ponytail`|ポニーテール|
|`twintail`|ツインテール|
|`half updo`|ハーフアップ|
|`hair in bun`|お団子ヘア|
|`dreadlocks`|ドレッドヘア|

### 髪色 (Hair Color)

※薄い色はプロンプトの前半に、濃い色は後半に配置すると色移りを防ぎやすい。

|**プロンプト**|**内容**|
|---|---|
|`black hair`|黒髪|
|`blonde hair`|金髪|
|`silver hair`|銀髪|
|`brown hair`|茶髪|
|`gradation color hair`|グラデーション|
|`multicolored hair`|複数色（ランダム）|
|`two-tone hair`|ツートンカラー|
|`inner color hair`|インナーカラー|
|`pastel hair`|パステルカラー|

### 髪の長さ (Length)

|**プロンプト**|**内容**|
|---|---|
|`very short hair`|ベリーショート|
|`short hair`|ショート|
|`medium hair`|ミディアム|
|`long hair`|ロング|
|`very long hair`|ベリーロング|
|`absurdly long hair`|お尻より長い髪|

### 髪質 (Texture)

|**プロンプト**|**内容**|
|---|---|
|`shiny hair`|艶のある髪|
|`silky hair`|シルクのような髪（細い）|
|`airy hair`|ふわふわした髪|
|`messy hair`|ボサボサ髪|
|`wet hair`|濡れた髪|

---

## 3. 表情に関するプロンプト (Expression)

### 喜び (Joy)

|**プロンプト**|**内容**|
|---|---|
|`smile`|微笑む|
|`laugh`|笑う|
|`grin`|ニヤリと笑う（歯を見せる）|
|`happy`|幸せそう|
|`great joy`|大喜び|
|`satisfied`|満足げ|

### 怒り (Anger)

|**プロンプト**|**内容**|
|---|---|
|`angry`|怒っている|
|`furious`|激怒|
|`frown`|眉をひそめる|
|`displeased`|不機嫌|
|`annoyed`|イライラしている|

### 悲しみ (Sadness)

|**プロンプト**|**内容**|
|---|---|
|`sad`|悲しい|
|`crying`|泣いている|
|`tearful`|涙ぐんだ|
|`wiping tears`|涙を拭う|
|`sob`|すすり泣く|
|`despairing`|絶望した|

### 驚き (Surprise)

|**プロンプト**|**内容**|
|---|---|
|`surprised`|驚いた|
|`astonished`|仰天した|
|`open mouth`|口を開ける（驚きで）|
|`screaming`|叫ぶ|
|`stunned`|呆然とした|

### その他 (Other)

|**プロンプト**|**内容**|
|---|---|
|`serious face`|真剣な顔|
|`blushing`|赤面|
|`wink`|ウインク|
|`sleepy face`|眠そう|
|`expressionless`|無表情|

---

## 4. 服装・外見に関するプロンプト (Clothing)

### トップス (Tops)

|**プロンプト**|**内容**|
|---|---|
|`t-shirt`|Tシャツ|
|`shirt`|シャツ|
|`blouse`|ブラウス|
|`sweater`|セーター|
|`hoodie`|パーカー|
|`cardigan`|カーディガン|
|`coat`|コート|
|`jacket`|ジャケット|
|`dress`|ワンピース/ドレス|
|`suit`|スーツ|
|`school uniform`|制服（セーラー服など）|
|`maid`|メイド服|
|`kimono`, `yukata`|着物、浴衣|

### ボトムス (Bottoms)

|**プロンプト**|**内容**|
|---|---|
|`skirt`|スカート|
|`pleated skirt`|プリーツスカート|
|`miniskirt`|ミニスカート|
|`pants`, `trousers`|ズボン|
|`denim`, `jeans`|ジーンズ|
|`shorts`|ショートパンツ|

---

## 5. その他の重要プロンプト（補完版）

※以下は記事後半のカテゴリに基づき、一般的な高頻度プロンプトを補完しています。

### ポーズ (Pose)

- `standing`（立ち姿）
    
- `sitting`（座っている）
    
- `looking at viewer`（こちらを見ている）
    
- `looking away`（よそ見）
    
- `arms behind back`（手を後ろで組む）
    
- `peace sign`（ピースサイン）
    

### 背景 (Background)

- `simple background`（シンプルな背景）
    
- `white background`（白背景）
    
- `indoor`, `room`（室内）
    
- `outdoor`, `street`（屋外、街）
    
- `nature`, `forest`, `beach`（自然、森、海）
    
- `night sky`, `starry sky`（夜空）
    

### 光・影 (Lighting)

- `cinematic lighting`（映画のような照明）
    
- `natural light`（自然光）
    
- `backlight`（逆光）
    
- `volumetric lighting`（立体的な光）
    

### 画質・クオリティ (Quality)

- `masterpiece`（傑作）
    
- `best quality`（最高品質）
    
- `high resolution`, `8k`, `4k`（高解像度）
    
- `highly detailed`（詳細な描き込み）
    

### ネガティブプロンプト（除外したい要素）

- `worst quality`, `low quality`（低品質）
    
- `bad anatomy`（崩れた人体）
    
- `missing fingers`, `extra digits`（指の欠損、多すぎる指）
    
- `nsfw`（性的表現の除外 ※必要な場合）
TEST



# TYPE-01｜ナチュラル実写セルフィー（カフェ／私服）
- Instagram / TikTok  
- 日常系AIグラビア  
- 「普通にいそう」なリアル感  
 **キーワード**  
`selfie` / `modern café` / `soft sultry` / `portrait mode`
 ```json
# {
  # "image_type": "Digital color selfie photograph of a real person in a close-up portrait style.",
  # "time_period_and_year": "Contemporary photography from the mid-2020s, based on modern casual fashion, high-resolution digital quality, and subtle color grading typical of smartphone selfies.",
  # "mood_and_vibe": "The image conveys a soft, intimate, and slightly sultry atmosphere with a calm yet alluring energy, evoking a sense of quiet confidence and subtle seduction in a relaxed indoor setting.",
  # "subject": "A young East Asian woman with a slender, delicate body morphology visible in the upper torso and arms; she holds a straight, neutral posture while facing the camera directly.",
  # "clothing": "She wears a fitted light gray crop top tank with a high crew neckline and racerback style, made of soft, slightly ribbed cotton-blend fabric that hugs the body closely; the hem ends just below the bust, revealing a slim midriff; additionally, a light beige or off-white knitted cardigan or long-sleeve layer is partially visible, draped loosely over her arms.",
  # "hair": "Medium-length straight hair in a warm light brown or dark blonde tone with subtle highlights, featuring blunt bangs across the forehead and soft, layered ends reaching the collarbone with a smooth, glossy texture.",
  # "face": "She has smooth, fair skin with a flawless, porcelain-like texture and natural glow; delicate facial features including large doe-like eyes with subtle neutral eyeshadow and mascara, a small straight nose, and full lips coated in glossy pink-nude lipstick; her expression is neutral and slightly pouty with a direct, engaging gaze toward the camera.",
  # "accessories": "A very thin, delicate gold or silver necklace with a tiny pendant resting at the collarbone.",
  # "action": "The woman is taking a selfie, holding the camera at arm's length while gazing directly into the lens with a calm, composed demeanor.",
  # "location": "An indoor modern café or lounge space with blurred background elements including wooden tables, cushioned seating, framed artwork or mirrors on the walls, and exposed ceiling pipes with track lighting.",
  # "lighting": "Mixed indoor lighting combining warm overhead spotlights and soft diffused natural light, producing gentle highlights and minimal shadows.",
  # "camera_angle_and_framing": "Eye-level selfie perspective with a medium close-up framing from the upper chest upward.",
  # "camera_equipment": "Modern smartphone front-facing camera using portrait mode with strong background blur.",
  # "style": "Realistic digital selfie aesthetic with soft neutral tones and polished social media finish.",
  # "negative_prompt": "blurry, low resolution, deformed features, extra limbs, unnatural skin texture, harsh shadows, flash lighting, cartoonish style"
# }'''
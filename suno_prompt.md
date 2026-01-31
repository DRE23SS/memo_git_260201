## Lyricsプロンプト設計（構成・演出の中核）

[🎵 Suno v5 楽曲プロンプト設計書（メタタグ,metatag）](https://zenn.dev/devp/articles/241a962af54c38)
### 構成タグ（メタタグ）

|タグ|役割|
|---|---|
|[Intro]|導入|
|[Verse]|Aメロ（物語）|
|[Pre-Chorus]|Bメロ（橋渡し）|
|[Chorus]|サビ（主題）|
|[Bridge]|Cメロ（転換）|
|[Interlude]|間奏|
|[Drop]|EDM的落差|
|[Buildup]|高揚前段階|
|[Theme]|主題提示|
|[Theme Reprise]|主題再提示|
|[Outro]|終結|

### 応用編：JSON構造化

```json
{
  "genre": "80s Japanese City Pop, Modern City Pop",
  "mood": ["nostalgic", "romantic", "night drive"],
  "bpm": 108,
  "key": "E Minor",
  "instruments": {
    "keys": "Rhodes electric piano (lush, chorus)",
    "bass": "synth bass (round, groovy)",
    "guitar": "clean electric (comping, subtle)",
    "drums": "vintage drum machine (tight, not aggressive)"
  },
  "production": {
    "stereo_image": "wide but balanced",
    "dynamics": "high dynamic range",
    "tone": "clean, glossy, tape saturation light",
    "reverb": "plate reverb (short to medium)"
  },
  "language": "Japanese"
}
```


## JSON形式のメリット（階層化と個別制御）

JSONは **“フォーム入力”のようにAIへ意味を渡す** 形式です。  
自然文よりも誤解が少なく、以下の利点があります。

1. **意味の一意化**  
    “ジャンル・楽器・音像”を明示的に区別でき、曖昧な解釈を防げます。
2. **階層化による精密制御**  
    instrumentsの中で各楽器を個別指定可能。  
    例：「鍵盤は温かいがドラムはドライ」などの差分表現が可能。
3. **再利用性とテンプレート化**  
    コピペで再利用しやすく、チーム共有も容易。
4. **差分更新が簡単**  
    bpmだけ変更など、要素単位で比較テストができる。
5. **モジュール化と優先制御**  
    productionブロックを音像モジュール化可能。
6. **可読性・教育性**  
    どの指示がどの結果を生んだか読み返しやすい。

---


# 演出タグ（拡張版）

## 🎤 ボーカル表現

- (whispering)：ささやく
    
- (softly)：優しく
    
- (powerfully)：力強く
    
- (sadly)：哀しげに
    
- (spoken)：語り
    
- (breathy)：息多め
    
- (octave double)：オクターブ重ね
    
- (harmonies: third above)：3度上のハモり
    
- (call and response)：掛け合い
    
- (ad-libs)：アドリブ的合いの手
    

## 🎸 楽器・編成

- [Instrument: Acoustic guitar (fingerstyle, gentle)]
    
- [Instrument: Strings (legato, warm)]
    
- [Instrument: 80s synth lead (delay dotted-8th)]
    
- [Layer: add pads] / [Layer: remove pads]
    
- [Mute: drums] / [Solo: piano]
    
- [Unison: bass & synth]
    

## 🎚 ダイナミクス・密度

- (building up)／(hold tension)／(explode)
    
- (sparse arrangement)／(thick arrangement)
    
- (pp)〜(ff)でも可
    

## 🕒 リズム・テンポ感

- (half-time groove)
    
- (double-time feel)
    
- [Time Signature: 7/8]
    
- [Swing: light]
    

## 🎹 ハーモニー・調性

- [Key: E Minor]
    
- [Modulation: +1 semitone at last chorus]
    
- [Cadence: plagal]
    
- コード指定例：[Am7] 君の [G] 横顔 [Cmaj7] 見ていた [F]
    

## 🌌 空間・音像

- (intimate close-mic)
    
- (stereo wide)
    
- (dry)／(cavernous reverb 4s)
    
- (tape saturation light)
    
- (low-pass filter intro)
    

## ⚡ トランジション・FX

- [FX: reverse cymbal rise]
    
- [FX: noise sweep up]
    
- [Transition: tape stop]
    
- [Beat Stop: 1 bar silence]
    

## 🏁 構造・終結

- [Double Chorus]
    
- [Breakdown]
    
- [Vamp: 4 bars]
    
- [Cold Ending]
    
- [Fade Out]
    

---

## 🚫 除外プロンプト（ネガティブプロンプト）

AIが自動で混入しやすい「ありがちな要素」を排除します。  
Styleプロンプトと組み合わせることで、思い通りの楽曲作成ができます。

ケース / 指定例

- ダークフォークで陽気要素回避：upbeat, happy, banjo, hand claps
    
- モダンCity Popで過度な80s排除：synth brass, slap bass, overly 80s sound
    
- Lo-fiで声素材除外：vocals, rap, spoken word, vocal samples
    

的外れな除外（例：クラシック曲からメタルを除外）は無意味です。

---

## 🈳 歌詞の読み間違いを防ぐテクニック（日本語向け）

Sunoは漢字やひらがなですら、読み間違えをするため、  
日本語歌詞ではかな表記またはローマ字表記を活用すると精度が向上します。

### 🎙 ひらがな化の例

まちのひかりが ながれていく  
まどに かさなる みずのせん

「感じ方」は損なわれますが、**音声的誤読（例：‘は’を‘ha’と読むなど）**が防げます。  
日本語母音が強調され、メロディとの整合性が良くなる場合もあります。

### 💡 助詞「は」問題（重要）

「は」は日本語でwaと発音されます。  
AIはこれを「ha」と読むことが多いため、ひらがな歌詞やローマ字表記では “wa” と明記します。

元の書き方 / 推奨表記 / 理由

- わたしは / わたしwa / 発音「わ」を明示
    
- これは / これwa / 誤読「これハ」防止
    
- はな / hana (名詞)／wa (助詞) / コンテキストで使い分け
    

推奨方法：

- 完全日本語詞の場合 → ひらがな歌詞
    
- 歌詞の英語混在・テンポ重視の場合 → ローマ字歌詞（助詞はwa）
    

---